# ai-memory

这个仓库由 [vibe-agent](https://github.com/liangzai927/vibe-agent) 自动创建，
用来在多台机器之间同步**记忆**和**会话记录**。

## 结构

```
memory/                             全局偏好——所有项目都读
projects/<项目名-哈希>/memory/        这个项目自己的偏好
projects/<项目名-哈希>/sessions/      这个项目的对话记录
```

目录名里的哈希来自项目的绝对路径，所以两个同名的项目不会撞。

## 注意

这里是**对话记录**。别把项目代码推到这个仓库里——两者互不相干。
