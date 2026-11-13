# 个人开源项目库

> 欢迎商务合作 — 微信：ylsh0628

本仓库收纳自建的开源小项目与 AI Agent 技能（Skill）。每个项目自成一个子目录，各自带 README。

---

## 目录

| 项目 | 说明 | 状态 |
|---|---|---|
| [tcm-inquiry](tcm-inquiry/) | 中医问诊采集 Skill —— 把患者的"结论式口述"转换成可用症状信息 | v1.0.0 |

---

## 关于 Skill

Skill 是给 AI Agent 用的能力包，通常是一个 `SKILL.md` 加若干 `references/` 参考资料，纯 Markdown，无脚本、无网络请求。

安装方式（以 WorkBuddy 为例）：把项目目录复制到 `~/.workbuddy/skills/<技能名>/`，目录名与 `SKILL.md` 中引用的相对路径保持一致即可。

---

## License

除各子目录另有声明外，本项目库采用 [MIT](LICENSE) 许可。
