###这里
 - 是对应的省份的MT7620系列的.so文件
 - arm目录下是梅林固件的so文件：
  - 梅林的使用方法：把对应的so文件下载后放入路由器/jffs/pppd/你的省份的so文件名
  - 拨号选用pppoe，在高级设置里面设置：plugin /jffs/pppd/你的省份的so文件名
###一定要保证时间的正确。请用各自校园的ntp服务器校对时间，地址不同，请自行查询ntp地址。