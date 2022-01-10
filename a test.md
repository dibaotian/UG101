
# 这是一个说明书

### hello world 

### 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMzU2OTg2MzE1XX0=
-->

####### 缩小心跳方案，将 commodity_number 2s商品种类， quality 信号质量 2s， device_function_switch 设备开关量 10S放到开机一次上报消息当中
FORMAT = '>2s2s15s4s4s4s11s11s20s15s2s2s10s'
prefix, msg_type, uuid, device_connect_type, venderid, version, device_longitude, device_latitude, \
device_iccid, device_imsi, commodity_number, quality, device_function_switch = struct.unpack(FORMAT, payload)
