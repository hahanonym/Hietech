# Hietech
## DCS Q&A 问题记录

### 1.DCS通过其他协议采集的数据点通过modbus协议映射支持的数据格式有哪些？
  
  * unsigned、ushort、uint16  signed、short、int16  int、int32、uint、uint32  float
  * 支持大小端模式设置
  
  

### 2.DCS modbus协议的WCF接口返回结果码有哪些？
  
  * 1=成功,2=超时,3=执行发生错误,4=其他错误
   
### 3.DCS modbus协议 某条总线上一两个仪表不稳定掉线上线跳变？
  
  * 网络状况很差或者总线繁忙，在指定时间（可设置）没有收到回复，尝试设置超时应答时间
  * 仪表本身有问题，残次品
