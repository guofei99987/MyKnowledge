ds = datastore('airlinesmall.csv','TreatAsMissing','NA');

ds.SelectedVariableNames = 'ArrDelay';%只选择ArrDelay列

read(ds)
readall(ds)
preview(ds)%预览

function maxArrivalDelayMapper (data, info, intermKVStore)
partMax = max(data.ArrDelay);
add(intermKVStore, 'PartialMaxArrivalDelay',partMax);

function maxArrivalDelayReducer(intermKey, intermValIter, outKVStore)
maxVal = -inf;
while hasnext(intermValIter)
   maxVal = max(getnext(intermValIter), maxVal);
end
add(outKVStore,'MaxArrivalDelay',maxVal);
