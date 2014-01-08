huzi-vim
========

使用vunble 让vim的配置和插件在自己的多个系统间的同步,这样以后方便多了

###使用方法：
####linux
<pre>
apt-get install vim gvim
git clone --recursive git@github.com:ImGeeker/huzi-vim.git ~/.vim
"install plugins:
:BundleInstall
"update plugins:
:BundleInstall!
"uninstall plugins:
:BundleClean"
</pre>
####mac
<pre>
brew install macvim
git clone --recursive git@github.com:ImGeeker/huzi-vim.git ~/.vim
ln -s ~/.vim/vimrc ~/.vimrc
</pre>

