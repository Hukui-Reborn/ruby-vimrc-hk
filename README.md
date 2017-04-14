# ruby-vimrc-hk （VIM设置备份）

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

## 如何使用

这里面大量配置来源于此：https://github.com/windy/ruby-vimrc

使用方法参见：https://ruby-china.org/topics/19315

snippets使用方法参见：http://hukui-blog.logdown.com/posts/2017/04/12/1697956
