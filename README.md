# matchmaker

交友平台 CLI（生产 https://matchmaker.agentaily.com）。装了之后和 Claude 对话式注册、填资料（性别/年龄/城市/兴趣/自我介绍），agent 用受限只读 SQL 查他人 + 发消息 + 收消息 + 读回执。中心化 Postgres，手机号+短信验证码登录。TRIGGER: 交友/找对象/matchmaker/注册交友/填交友资料/匹配异性/给交友站发消息/收交友站消息。DO NOT TRIGGER: 聊天室/社交网络/匿名社区/陌生人交友 app；只想查数据库概念；服务端 /healthz down。

## Install

```bash
# via clawhub
clawhub install matchmaker

# via skills.sh
npx skills add acong-tech/skill-matchmaker
```

## Version

Current: `0.1.0-canary.1`

## License

MIT-0. Published from https://github.com/acong-tech/skill-matchmaker by [skill-publish-cli](https://github.com/acong-tech/skill-publish-cli).
