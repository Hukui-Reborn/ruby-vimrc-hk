# ruby-vimrc-hk （VIM设置备份）
## 2017-4-21更新：
- vimrc中增加了Ack快速搜索工具，可以快速搜索整个项目。
- vimrc中添加了vim-coloresque来显示css的颜色代码的实际颜色。
## 备份说明

- vimrc为配置文件
- snippets/eruby.snippets 修改添加了lt,lt",ltd三个snippets。
- snippets/markdown.snippets 修改添加了orid 这个 snippets .
- snippets/rails.snippets 修改了flash 这个 snippets, 把单引号变成了双引号,以便兼容#{}.
- colors/molokai.vim为颜色配置文件

## 使用说明：

安装好vim（大于7.3即可）之后（安装方法`brew install vim`），继续输入以下指令:

```bash
# 安装 Vundle( vim 插件管理器 )
$ git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
# 从远程拉下备份文件
$ git clone https://github.com/Hukui-Reborn/ruby-vimrc-hk.git
# 把配置复制到.vimrc中
$ cp ruby-vimrc-hk/vimrc ~/.vimrc
# 新增VIM配色文件夹
$ mkdir ~/.vim/colors
# 将molokai.vim配色文件拷贝到配色文件夹
$ cp ruby-vimrc-hk/colors/molokai.vim ~/.vim/colors
# 打开vim
$ vim
  # 在VIM界面输入以下指令
  :PluginInstall
  # 等待插件安装完成, 重启 vim
  :q!
```
如果你也想使用我修改后的 snippets, 请进行如下操作:
```
 cp ~/ruby-vimrc-hk/snippets/markdown.snippets ~/.vim/bundle/vim-snippets/snippets/markdown.snippets
 cp ~/ruby-vimrc-hk/snippets/rails.snippets ~/.vim/bundle/vim-snippets/snippets/rails.snippets
 cp ~/ruby-vimrc-hk/snippets/eruby.snippets ~/.vim/bundle/vim-snippets/snippets/eruby.snippets
```

## 如何使用

这里面大量配置来源于此：https://github.com/windy/ruby-vimrc

使用方法参见：http://hukui-blog.logdown.com/posts/2017/04/13/configuration-of-vim-for-ruby-development-explore

snippets使用方法参见：http://hukui-blog.logdown.com/posts/2017/04/12/1697956
