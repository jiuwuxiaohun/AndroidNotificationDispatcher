# Android 监控微信/支付宝/QQ收款监控程序

用于监控 Android 支付宝/微信/QQ的收款通知，需要权限 **通知管理权限**、后续看情况做 **无障碍**
> 此Android源码实现了微信/支付宝免签支付, 和市面上各种收费的免签支付平台实现方式大致原理都相同
>
> 服务端功能也已实现, 流程已全部跑通, 稳定运行, 需要微信支付宝免签接口的可联系本人, 需要服务端代码也可联系本人
>
> 无障碍每次都要授权，弄到服务器上可能会好一点，再加上自动读取收款记录收款码啥的。

## TODO

- [x] 通知管理权限
    - [x] 监控并推送支付宝微信通知内容
- [ ] 无障碍控制权限
    - [ ] 自动读取收费列表
- [ ] 收费历史记录
- [ ] 自动激活

## 原理

监控手机通知，推送消息到服务器

## 注意

- 支付宝微信需要日常后台打开接受通知
- 微信需要打开语音收款


![](https://ae01.alicdn.com/kf/HTB1ksu3atfvK1RjSspo762fNpXap.png)

![](https://ae01.alicdn.com/kf/HTB14HxRzMHqK1RjSZFk760.WFXaf.png)

![](https://ae01.alicdn.com/kf/HTB1W0G4ayfrK1RjSspb7634pFXal.png)
