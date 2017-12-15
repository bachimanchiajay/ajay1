# connecting mysql db to python
import pymysql.cursors
import pyhadoop
db=pymysql.connect(user='root',password='AJITH',db='details')
a= db.cursor()
sql=("select * from details1")
a.execute(sql)
row=a.execute(sql)
for row in a:
    print(row)import pymysql.cursors
import pyhadoop
db=pymysql.connect(user='root',password='AJITH',db='details')
a= db.cursor()
sql=("select * from details1")
a.execute(sql)
row=a.execute(sql)
for row in a:
    print(row)
