# tmux-config

我的 tmux 配置文档，基于 [.tmux](https://github.com/gpakosz/.tmux)  进行开发

### 特性

1. `<prefix>` 键盘是 ^a 或 ^b
1. `^n` 切换到下一个 window
1. `^N` 切换到上一个 window
1. `<prefix> c` 新建一个 window
1. `<prefix> -` 横分屏（pane）
1. `<prefix> _` 横分屏（pane）


### 需求

1. tmux >= 2.1 版本
1. 在 tumx 外面，$TERM 必须是 xterm-256color

### 安装

    cd
    git clone https://github.com/shishirui/tmux-config.git
    cp -r tmux-config/.tmux.conf vim-config/.tmux.conf.local .

### 配置

打开 `.tmux.conf` 文件可以进行进一步配置。
