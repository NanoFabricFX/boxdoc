# 数据字典

网关内部分数据字典

###### device_state

``` json
{
    "Online":0,
    "Offline":1
}
```

###### valuetype

``` json
{
    "Int16": 1,
    "Float": 2,
    "Bool":3,
    "Int32":4,
    "Int64":5,
    "Double": 6,
    "String": 7,
    "Int8": 8
}
```


##### Fanuc

###### cnc_mode

``` json
{
    "Mdi":0,
    "Memory":1, 
    "None":2,
    "Edit":3, 
    "Handle":4,
    "Jog":5, 
    "TeachinJog":6,
    "TeachinHandle":7,
    "Incfeed":8,
    "Reference":9,
    "Remote":10,
    "Other":11
}
```

###### cnc_runstatus

``` json
{
    "RESET":0,
    "STOP":1, 
    "HOLD":2,
    "START":3, 
    "MSTR":4,
    "Other":5
}
```

###### cnc_emer

``` json
{
    "NotEmergency":0,
    "Emergency":1, 
    "Reset":2,
    "Wait":3, 
    "Others":4
}
```


###### cnc_gcode

``` json
{
    "G01":0,
    "G02":1, 
    "G03":2,
    "G04":3, 
    "Others":4
}
```




##### Mitsubishi

###### cnc_mode

``` json
{
    "JOG模式中":0,
    "手轮模式中":1, 
    "增量模式中":2,
    "手动任意进给模式中":3, 
    "参考点返回模式中":4,
    "自动初始设定模式中":5, 
    "JOG手轮同时模式中":6,
    "Null1":7,
    "内存模式中":8,
    "纸带模式中":9,
    "在线运行模式中":10,
    "MDI模式中":11,
    "Null2":12,
    "Null3":13,
    "子系统控制I运行模式中":14,
    "Null4":15
}
```
###### cnc_runstatus

``` json
{
    "RESET":0,
    "STOP":1, 
    "HOLD":2,
    "START":3, 
    "Others":4
}
```


###### cnc_emer

``` json
{
    "NotEmergency": 0,
    "Emergency": 1
}
```

##### SiemensCNC

###### cnc_mode

``` json
{
    "JOG": 0,
    "TEACHIN":1, 
    "MDA":2,
    "AUTO":3, 
    "REPOS":4,
    "REFPOINT":5, 
    "VAR":6,
    "INC":7,
    "OTHER":8
}
```

###### cnc_runstatus

``` json
{
    "RESET":0,
    "STOP":1, 
    "HOLD":2,
    "START":3, 
     "SPENDLE_CW_CCW":4,
     "Others":5
}
```