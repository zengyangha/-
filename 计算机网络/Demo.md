## 交换机：通过内部MAC地址表决定信息流向，接入交互机的设备都必须有自己的MAC地址（相当于与设备的UUID）

## 泛洪（Flooding）： 在报文里写上自己的MAC地址和目标MAC地址， 该接口的MAC，第一次会发给所有人，其他机器收到但MAC不对时会丢弃，目标机收到后会发送确认信息，而第二次传输时则不会发给所有人，

## IP地址：MAC地址是和设备绑定的，如果电脑的网卡更换了或是其他原因导致MAC改变了，那得重新泛洪，所以有了抽象的地址：IP地址，设备可通过IP地址获取MAC地址
