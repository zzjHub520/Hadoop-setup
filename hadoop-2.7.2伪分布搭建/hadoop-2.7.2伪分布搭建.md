vim hadoop-env.sh

![image-20211124234654444](hadoop-2.7.2伪分布搭建.assets/image-20211124234654444.png)



vim core-site.xml

![image-20211124234932367](hadoop-2.7.2伪分布搭建.assets/image-20211124234932367.png)



vim hdfs-site.xml

![image-20211124235102352](hadoop-2.7.2伪分布搭建.assets/image-20211124235102352.png)



vim yarn-env.sh

![image-20211124235248753](hadoop-2.7.2伪分布搭建.assets/image-20211124235248753.png)



vim yarn-site.xml

![image-20211124235420643](hadoop-2.7.2伪分布搭建.assets/image-20211124235420643.png)



vim mapred-site.xml

![image-20211124235648425](hadoop-2.7.2伪分布搭建.assets/image-20211124235648425.png)



启动

```
bin/hdfs namenode -format
sbin/start-all.sh
```

![image-20211125000036943](hadoop-2.7.2伪分布搭建.assets/image-20211125000036943.png)