# 创建
```py
cx = sqlite3.connect("E:/test.db")
```
>存在则打开，不存在则创建

# 操作

- commit()--事务提交
- rollback()--事务回滚
- close()--关闭一个数据库连接
- cursor()--创建一个游标

# 游标
```
cu = cx.cursor()
```
这样定义了一个游标。游标对象有以下的操作：

- execute()--执行sql语句
- executemany--执行多条sql语句
- close()--关闭游标
- fetchone()--从结果中取一条记录，并将游标指向下一条记录
- fetchmany()--从结果中取多条记录
- fetchall()--从结果中取出所有记录
- scroll()--游标滚动

## 建表

```py
cu.execute('create table catalog (id integer primary key,pid integer,name varchar(10) UNIQUE)')
```

## 插入数据

```py
cu.execute("insert into catalog values(0, 0, 'name1')")
cu.execute("insert into catalog values(1, 0, 'hello')")
cx.commit()
```

## 查询数据
```py
cu.execute('select * from catalog')
cu.fetchall()
```

## 修改数据
```
cu.execute("update catalog set name='name2' where id = 0")
cx.commit()
```

## 收尾
```
cu.close()
cx.close()
```
