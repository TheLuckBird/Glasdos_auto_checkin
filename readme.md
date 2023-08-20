# Checkin

GitHub Actions 实现 [GLaDOS][glados] 自动签到

([GLaDOS][glados] 可用邀请码: `MW4DK-O0RSF-C7AOU-EN1MP`, 双方都有奖励天数)

## 使用说明

1. Fork 这个仓库

1. 登录 [GLaDOS][glados] 获取 Cookie
   ![image](https://github.com/TheLuckBird/Glasdos_auto_checkin/assets/97025498/b114300b-7e54-4586-b0c4-359366e41c44)


1. 添加 Cookie 到 Secret `GLADOS`

1. 启用 Actions, 每天北京时间 00:10 自动签到
   ![image](https://github.com/TheLuckBird/Glasdos_auto_checkin/assets/97025498/b50f2f29-ad1f-43b0-9c86-c471d9f23f48)


1. 如需推送通知, 可用 [PushPlus][pushplus], 添加 Token 到 Secret `NOTIFY`

[glados]: https://github.com/glados-network/GLaDOS
[pushplus]: https://www.pushplus.plus/
