# 流量自动调度
#### 为京东商城大促期间提供流量的自动调度保障；用户的分布式接入IP网络质量出现问题，将流量切换至备用分布式接入IP地址，当主ip恢复可用性后，流量从备用ip切回主ip
* 通过人为干预的方式手动降低触发阀值，观察自动化流量调度能否及时发现灾情，并启动流量调度
* 将阀值升高，自动化流量调度能及时发现，并将流量切回
