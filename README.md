# 我的vim/neovim的配置文件

vim的配置文件的目录为`~/.vimrc`
neovim的配置文件的目录为`~/.config/nvim/init.vim`

## 环境
[coc.nvim](https://github.com/junegunn/vim-plug)

下载`coc.nvim`
`sudo su` 输入密码后进入root权限下后`curl -sL install-node.now.sh/lts | bash`

最后`PlugInstall`

按键|映射|作用
-|-|-
`sl` | `set splitright<CR>:vsplit<CR>` | 向右分屏
`sh` | `set nosplitright<CR>:vsplit<CR>` | 向左分屏
`sj` | `set splitbelow<CR>:split<CR>` | 向下分屏
`sk` | `set nosplitbelow<CR>:split<CR>` | 向上分屏
`F4` | `call HeadFile()<CR>` | 添加头文件
`ctrl+n` | `:NERDTreeToggle<CR>` | 打开NERDTree
`F8` | `<Plug>MarkdownPreview ` | 打开markdown预览
`F9` | `<Plug>StopMarkdownPreview ` | 关闭markdown预览
`F5` | `call CompileRunGcc()<CR>` | 判断文件类型并编译
