**GLADOS注册**

1、打开 <https://github.com/glados-network/GLaDOS> ，找到[**\*Register***]，打开链接，填写邮箱进行登录。

2、输入激活码`4MSZ9-1WFJ8-4TLKD-Q1A9Z`，进行激活，获得3天试用。

3、点击签到可以增加一天

**自动签到原理**

1. github 的 actions 可以免费执行代码
2. github 的 actions 可以定时调度

**自动签到方式**

1. fork 此项目
2. 在 fork 出的项目中设置 cookie
3. 不做任何操作,即可在每天的 7.30 分进行自动签到


**帮助**
> 打开chrom, 登录到 glados 控制台, 找到签到按钮, 按f12, 拿到cookie  

![image](https://user-images.githubusercontent.com/23112609/96143045-50e80b80-0f35-11eb-8b84-61bcc2f2dac4.png)

> 在fork 出项目下的 `Secrets`中 设置 cookie

![image](https://user-images.githubusercontent.com/23112609/96195429-536f5300-0f7f-11eb-9c97-bf35bfcfdca0.png)

> 随意改下 readme 进行 push 触发 action

> 在 fork 出项目下的 `actions` 查看运行历史日志来确认签到结果

![image](https://user-images.githubusercontent.com/23112609/96226413-29408400-0fc5-11eb-9ef2-044aac8642e1.png)
