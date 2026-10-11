# 记忆（Cuckoo Code 插件）

长期记忆的**管理界面**：列表、新建、编辑、删除。数据与 AI 的 `remember` 工具共享——你在界面改完，AI 下一轮就能看到。

## 安装

在 Cuckoo Code 的「插件市场」搜索 **记忆**，一键安装。

## 功能

- **列表**：所有记忆（跨会话、跨项目保留）
- **新建 / 编辑 / 删除**：不用等 AI 记，自己手动管
- **与 AI 共享**：界面改的，AI 下轮就知道；AI 记的，界面立刻出现

## 数据位置

`~/.cuckoo/memories.json`

## 依赖

需要 Cuckoo Code ≥ 0.8.8（提供 `shellAPI.listMemories` 等 IPC）。

## 许可证

MIT
