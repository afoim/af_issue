# af_issue

AcoFork 官方项目问题反馈仓库。

本仓库专门接收 AcoFork 项目及其站点、服务的：

- 功能故障和异常
- 页面样式或响应式问题
- 账号、登录、权限问题
- 性能、接口或服务异常
- 计费、积分和订单问题
- 新功能建议
- 使用方法咨询

本仓库只处理项目相关问题，不用于闲聊、情感话题或与 AcoFork 无关的网站反馈。

## 提交 Issue

请从 [新建 Issue](https://github.com/afoim/af_issue/issues/new/choose) 开始，并选择最符合情况的表单：

| 表单 | 适用场景 |
| --- | --- |
| [问题反馈](https://github.com/afoim/af_issue/issues/new?template=bug_report.yml) | 已经发生的功能、页面、账号、性能、服务或计费问题 |
| [新功能建议](https://github.com/afoim/af_issue/issues/new?template=feature_request.yml) | 希望项目新增某项功能、页面或服务能力 |
| [使用咨询](https://github.com/afoim/af_issue/issues/new?template=question.yml) | 询问功能用法、操作流程或相关规则 |

普通用户不能直接创建空白 Issue，必须先填写表单。维护者仍可以在需要时创建空白 Issue。

## 域名范围

提交的问题、建议或咨询必须与以下域名之一有关：

- `2x.nz`
- `*.2x.nz`
- `acofork.com`
- `*.acofork.com`

例如：

- `i.2x.nz`
- `www.acofork.com`
- `status.acofork.com`
- `api-xxx.acofork.com`

表单会要求你先确认问题属于上述域名范围。与其他域名无关的问题，请不要提交到这里。

## 如何描述问题

问题反馈至少应包含：

1. 发生了什么
2. 如何复现
3. 你期望出现什么结果
4. 使用的页面、设备或浏览器环境
5. 必要时附上脱敏后的截图或日志

如果你熟悉浏览器开发者工具，还可以填写高级定位信息：

- **当前所在页面 URI**：你当时打开的完整 URI，例如 [https://www.acofork.com/account/](https://www.acofork.com/account/)
- **实际失败请求 URI**：页面请求失败的 API 或资源 URI，例如 [https://i.2x.nz/api/login](https://i.2x.nz/api/login)
- **请求时的地理位置**：中国大陆 / 非中国大陆
- **使用的设备**：移动端 / PC端
- **使用的浏览器**：名称和版本，例如 `Microsoft Edge 版本 151.0.4129.107 (正式版本) (64 位)`

在前后端分离的架构中，当前页面正常打开并不代表后端请求正常。例如账号页面无法登录时，真正失败的可能是登录 API 的 CORS、字段校验或鉴权逻辑。此时请尽量同时填写当前页面 URI 和实际失败请求 URI。

URI 中如果包含查询参数，请先删除或脱敏 Token、Cookie、验证码、密钥等敏感值。

## 隐私与安全

这是公开仓库。请不要在 Issue、评论或截图中提交：

- 密码、Token、Cookie、验证码和私钥
- 手机号、邮箱、真实姓名、地址等不必要的个人信息
- 订单号、付款截图和完整支付凭证
- 未脱敏的请求头、响应体或日志

如果你发现安全漏洞，请使用 [Security → Advisories → Report a vulnerability](https://github.com/afoim/af_issue/security/policy) 私密提交，不要公开创建 Issue。

如果敏感信息已经被公开，请立即删除相关内容，并尽快撤销或更换已经暴露的凭据。

## Issue 处理

维护者会根据内容添加 Label，并可能要求补充信息、等待复现或合并重复 Issue。与项目无关、信息不足、重复或公开披露安全漏洞的 Issue，可能会被关闭或引导到其他入口。

Issue 用于项目反馈，不是实时客服渠道，因此不保证即时回复。

相关页面：

- [Issue 列表](https://github.com/afoim/af_issue/issues)
- [Label 列表](https://github.com/afoim/af_issue/labels)
- [安全策略](https://github.com/afoim/af_issue/security/policy)
- [隐私提交说明](https://github.com/afoim/af_issue/blob/main/.github/SECURITY.md)
