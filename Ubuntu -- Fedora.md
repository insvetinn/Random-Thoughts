# Ubuntu --> Fedora

0. 制作启动盘

	[BalenaEtcher](https://www.balena.io/etcher/)

1. System

	[Fedora Workstation](https://getfedora.org/en/workstation/)

2. Private Information

	+ Personal Account
		+ Firefox Account Recover Key * 2
		+ Qv2ray Subscription

	+ Personal Ebooks, Photos, Pictures, Music, Video, .sf2

	+ Special & Unique

		+ Irisu Syndrome Metsu!

		+ 砂糖菓子の弾丸は撃ちぬけない

3. Software

	+ p7zip

	+ Browser
		+ [Firefox](https://www.mozilla.org/en-US/firefox/new/)

	+ Network
		+ [Qv2ray](https://qv2ray.net/)

	+ Audio / Video Decoding

		+ [ffmpeg](https://ffmpeg.org/)

		+ flash

			```sh
			sudo apt install flashplugin-installer
			sudo apt install browser-plugin-freshplayer-pepperflash
			```

	+ Text Editor

		+ Vim

			+ configure: 

				```.vimrc
				:set nu
				set cursorline
				
				" Vundle Configurations
				set nocompatible              " be iMproved, required
				filetype off                  " required
				
				" set the runtime path to include Vundle and initialize
				set rtp+=~/.vim/bundle/Vundle.vim
				call vundle#begin()
				" alternatively, pass a path where Vundle should install plugins
				"call vundle#begin('~/some/path/here')
				
				" let Vundle manage Vundle, required
				Plugin 'VundleVim/Vundle.vim'
				
				" The following are examples of different formats supported.
				" Keep Plugin commands between vundle#begin/end.
				" plugin on GitHub repo
				Plugin 'tpope/vim-fugitive'
				" plugin from http://vim-scripts.org/vim/scripts.html
				" Plugin 'L9'
				" Git plugin not hosted on GitHub
				Plugin 'git://git.wincent.com/command-t.git'
				" git repos on your local machine (i.e. when working on your own plugin)
				Plugin 'file:///home/gmarik/path/to/plugin'
				" The sparkup vim script is in a subdirectory of this repo called vim.
				" Pass the path to set the runtimepath properly.
				Plugin 'rstacruz/sparkup', {'rtp': 'vim/'}
				" Install L9 and avoid a Naming conflict if you've already installed a
				" different version somewhere else.
				" Plugin 'ascenator/L9', {'name': 'newL9'}
				
				" All of your Plugins must be added before the following line
				call vundle#end()            " required
				filetype plugin indent on    " required
				" To ignore plugin indent changes, instead use:
				"filetype plugin on
				"
				" Brief help
				" :PluginList       - lists configured plugins
				" :PluginInstall    - installs plugins; append `!` to update or just :PluginUpdate
				" :PluginSearch foo - searches for foo; append `!` to refresh local cache
				" :PluginClean      - confirms removal of unused plugins; append `!` to auto-approve removal
				"
				" see :h vundle for more details or wiki for FAQ
				" Put your non-Plugin stuff after this line
				
				Plugin 'Valloric/YouCompleteMe'
				```

	+ IME

		+ [Rime](https://rime.im/)
		+ [IBus Tweaker](https://extensions.gnome.org/extension/2820/ibus-tweaker/)

	+ Language

		+ Mysql

			```sh
			sudo apt install mysql-server
			sudo systemctl start mysql.service
			sudo mysql_secure_installation
			create user 'username'@'host' identified with by 'password';
			```

		+ Java

			+ [Idea Community](https://www.jetbrains.com/idea/download/#section=linux)
				+ configure: set all tab == 8 spaces
				+ plugin: JavaFX
				+ SceneBuilder

		+ Others: Python3, Lua, R, Julia

	+ Markdown editor
		+ Typora

	+ Video Player
		+ VLC Media Player

	+ Picture Viewer
		+ Open Comic for .webp

	+ Pixel Tool
		+ Aseprite
	+ Sketch Tool
		+ Krita

	+ Photo Tool
		+ GIMP

	+ Video Tool
		+ OBS

	+ Ebook Reader
		+ Okular
	+ Font
		+ CHO Pixel Code, Zpix, CtrlZpix
		+ Gnome Tweaker

	+ Music Sheet Tool
		+ MuseScore
	+ 键盘映射
		+ Input Remapper

	+ 3D Modeling
		+ Blender

	+ Clock
		+ Pomatez

	+ Digital Circuit Simmulator
		+ Logisim Evolution

	+ Remote Connection
		+ ssh
		+ Remmina

	+ EXE Runner
		+ wine
		+ winetricks

	+ Game
		+ Steam

	+ Others
		+ Aegisub