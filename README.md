# Binance_CopyTrading_Assistant_V3_Tracker
# 币安交易信号追踪器

后台追踪，网页后台管理

XT交易所注册链接（高额返佣奖励）：https://www.xt.com/zh-CN/accounts/register?ref=RJKFGL
![image](https://github.com/user-attachments/assets/b444fc17-78be-472c-843b-d5efcf9c0d03)

## Step 1
账号注册：
~~https://www.funsound.cn/tracker~~
无需登录，免费开放

软件下载：
https://github.com/lazyer-trading/Binance_CopyTrading_Assistant_V3_Tracker/releases

## Step 2
运行软件，支持windows/linux, 建议服务器长期运行

[windows]

![alt text](img/img1.png)
![image](https://github.com/user-attachments/assets/353821e7-9a19-463e-9391-58a2293df7d2)

[linux]

后台运行： nohup ./tracker_server > run.log 2>&1 &

关闭后台: ps -ef | grep ./tracker_server | awk '{print $2}' | xargs kill -9

## Step 3
打开后台管理
> 本地管理：http://localhost:7777

> 远程管理：http://{server_ip}:7777 (可以部署在linux服务器)

![alt text](img/img2.png)


获取交易员id
![alt text](img/img3.png)

关闭网页不影响后台运行



# 联系我们
#### Telegram: [@lazyer_trading](https://t.me/bn_ct_track)
#### Email: [lazyer.trading@gmail.com](mailto:lazyer.trading@gmail.com)
