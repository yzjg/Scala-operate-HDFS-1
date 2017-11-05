##Scala操作HDFS
###需求
HDFS路径：

/spark/emp/temp/201711112025/d=20171111/h=20/_SUCCESS  空文件
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00000-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00001-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00002-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00003-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00004-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00005-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00006-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00007-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt
/spark/emp/temp/201711112025/d=20171111/h=20/part-r-00008-6ba69620-ba52-4cb1-9ea0-6634ae0e16bc.txt

===>

要求：使用Scala操作HDFS文件系统， 17111125<=201711112025  01...  计数

/spark/emp/data/d=171111/h=20/17111125-01.txt
/spark/emp/data/d=171111/h=20/17111125-02.txt
/spark/emp/data/d=171111/h=20/17111125-03.txt
/spark/emp/data/d=171111/h=20/17111125-04.txt
/spark/emp/data/d=171111/h=20/17111125-05.txt
/spark/emp/data/d=171111/h=20/17111125-06.txt
/spark/emp/data/d=171111/h=20/17111125-07.txt
/spark/emp/data/d=171111/h=20/17111125-08.txt
/spark/emp/data/d=171111/h=20/17111125-09.txt