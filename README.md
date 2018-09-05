# tmux-config

我的 tmux 配置文档，基于 [gpakosz/.tmux](https://github.com/gpakosz/.tmux)  进行开发

### 常用的快捷键

1. `<prefix>` 键盘是 ^a 或 ^b
1. `^n` 切换到下一个 window
1. `^N` 切换到上一个 window
1. `<prefix> c` 新建一个 window
1. `<prefix> -` 横分屏（pane）
1. `<prefix> _` 竖分屏（pane）
1. `<prefix> m` 切换鼠标模式开启或关闭（启用后可以用鼠标选择 pane、window，调整 pane 大小等）
1. `<prefix> Enter` 进入复制模式 （按 Esc 退出）
1. `<prefix> s` 列出 session，支持切换
1. `<prefix> d` 将 session 放入后台（放入后台后，可以用 `tmux a` 或 `tmux a -t [序号]` 切回来）


更多快捷键请前往 [gpakosz/.tmux](https://github.com/gpakosz/.tmux) 进行了解

### 需求

1. tmux >= 2.1 版本
1. 在 tumx 外面，$TERM 必须是 xterm-256color

### 安装

    cd
    git clone https://github.com/shishirui/tmux-config.git
    cp -r tmux-config/.tmux.conf vim-config/.tmux.conf.local .

### 配置

打开 `.tmux.conf` 文件可以进行进一步配置。
