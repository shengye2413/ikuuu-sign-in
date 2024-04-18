# ikuuu每日签到

本项目fork自<a href = 'https://github.com/bighammer-link/jichang_dailycheckin'>此处</a>做出少量修改,在此感谢！
## 推送
 采用企业微信推送方式



# 部署过程

1. 右上角Fork此仓库
2. 然后到`Settings`→`Secrets and variables`→`Actions` 新建以下参数：

| 参数   |  内容  |
| ------------ |  ------------ |
| EMAIL  |  账号邮箱  |
| PASSWD |  账号密码  |
| WEBHOOK |  企业微信机器人URL  |

3. 到`Actions`中创建一个workflow，运行一次，以后每天项目都会自动运行。
4. 最后，可以到Run sign查看签到情况，同时也会也会将签到详情推送到企业微信。
