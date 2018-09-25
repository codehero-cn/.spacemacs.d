###安装使用
安装emacs
安装spacemacs:git@github.com/syl20bnr/spacemacs.git  ~/.emacs.d
安装本配置:git@github.com:codehero-cn/.spacemacs.d.git ~/.spacemacs.d

###文件结构
|--bak/   重要init.el文件备份
|--init.el
|--Readme.md

###原始配置生成
安装emacs
安装spacemacs:下载https://github.com/syl20bnr/spacemacs.git  20180925 download zip spacemacs-master.zip
解压后放到~/.emacs.d/目录下  

第1次运行emacs,自动启动配置向导Dotfile wizard installer
1).What is your preferred editing style?
->On the planet Emacs in the Holy control tower(emacs)
  Among the starts aboard the Evil flagship (vim)
2).What distribution of spacemacs would you like to start with?
->The standard distribution,recommended (spacemacs)
  A minimalist distribution that you can build on (spacemacs-base)
3).What type of completion framework do you want?
->A heavy one but full-featured (helm)
  A lighter one but still very powerful (ivy)
  None (not recommended)  

下载插件启动完成,自动生成~/.spacemacs文件
建立~/.spacemacs.d,并move ~/.spacemacs to ~/.spacemacs.d/init.el
Note: ~/.spacemacs will always take priority over ~/.spacemacs.d/init.el, so ~/.spacemacs must not exist for ~/.spacemacs.d/init.el to be used by Spacemacs.
开始自己的个性化配置...












