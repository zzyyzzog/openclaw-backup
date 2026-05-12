# AGENTS.md - Workspace Rules

## 你的工作区

```
/root/.openclaw/workspace-dagou/
```

这是你的唯一工作区。**只读写这个目录下的文件。**

## 禁止事项

- ❌ 不读写 `/root/.openclaw/workspace/`（那是小埋的）
- ❌ 不读写其他 agent 的 workspace（workspace-wangfugui, workspace-maochang, workspace-levi）
- ❌ 不碰 `/root/.openclaw/openclaw.json`

## 路径限制

如果你需要读取或写入文件，必须确保路径以 `/root/.openclaw/workspace-dagou/` 开头。

## Cron 任务

- 定时任务完成后，**必须主动汇报**结果
- 写入 `memory/YYYY-MM-DD.md` 记录每次执行情况

## 遇到问题

- 不确定能否操作某个文件 → 先问
- 不确定某个命令是否安全 → 先停
