# 漏水传感器LeakSensor
工作电压:24V

LeakSensor.eprj 是嘉立创EDA工程文件,里面做了器件标准化, 直接嘉立创下单

这个不用刷代码很简单的
信号高电平就是有泄漏


![alt text](image.png)
探头就是两根线插在海绵里

把探头粘在你的管壁上
漏水进去海绵湿了就会提示

# 连接pixhawk
将leak sensor的信号口(signal 3 )插到pixhawk的AUX OUT6

![alt text](image-1.png)

进入QGC设置界面
![alt text](image-2.png)