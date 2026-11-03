# tianting-desktop

天听 PC 客户端（Tauri 壳）。**天听**是自研 IM 平台，替换腾讯 IM（聊天、群聊、聊天室、站内推送）。

天听的 PC 客户端：用 Tauri 2 包装 tianting-web 的界面，桌面宽屏三栏布局。

| | |
|---|---|
| 状态 | 尚未开始，排在工作队列 Q16（M4） |
| 技术 | Tauri 2（需要安装 Rust，待授权），加载 tianting-web |
| 服务端、协议、需求文档 | [tianting-server](https://github.com/leetonny001/tianting-server) |
| 工作队列 / 日报 | tianting-server 的 `docs/process/QUEUE.md`、`docs/reports/daily/` |

Rust 装不了时退回 Electron（见 tianting-server 的 `docs/PLAN.md` 3.1 节）。

## 天听的项目

| 仓库 | 内容 |
|---|---|
| [tianting-server](https://github.com/leetonny001/tianting-server) | Go 服务端、协议、需求 / 架构 / 测试文档 |
| [tianting-sdk-ts](https://github.com/leetonny001/tianting-sdk-ts) | SDK（TypeScript）：H5、PC |
| [tianting-sdk-kotlin](https://github.com/leetonny001/tianting-sdk-kotlin) | SDK（Kotlin）：Android |
| [tianting-sdk-swift](https://github.com/leetonny001/tianting-sdk-swift) | SDK（Swift）：iOS |
| [tianting-web](https://github.com/leetonny001/tianting-web) | H5 客户端 |
| [tianting-desktop](https://github.com/leetonny001/tianting-desktop) | PC 客户端 |
| [tianting-android](https://github.com/leetonny001/tianting-android) | Android 客户端 |
| [tianting-ios](https://github.com/leetonny001/tianting-ios) | iOS 客户端 |
| [tianting-admin](https://github.com/leetonny001/tianting-admin) | 管理后台 H5 |
| [tianting-ops](https://github.com/leetonny001/tianting-ops) | 运维后台 H5 |
