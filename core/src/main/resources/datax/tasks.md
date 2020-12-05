config
```properties
#json文件根目录相对路径头配置，配置此参数允许后续以<dit>/xxx的形式配置json文件位置
pathhead=impalatask
#具体相对路径头对应的路径
impalatask=D:\tmp\impalatask
```
注意:下面这行end config是配置结束标识，不要改动，否则会导致配置无法识别
end config


下面开始写配置json的路径，只要放在```代码块里的且不是以#开头就能识别,按顺序从上到下执行

1、同步业务表json
```
<impalatask>kudu_mysql_costLedger.json
```
