macos setup for web developpement
===================

This is what is use to work. Mabye not what you should use. I mainly do front end js with ember and meteor. So, zero python, zero ruby for me and a very little PHP for me.

At first, check updates via the appstore.

## Basic settings

In the system preferences

* general
	* icon size > small
* desktop > choose a nice wall paper !
* dock
	* small size, small magnifiying
	* bottom
	* hide automatically
* mouse / trackpad
	* desactivate natural way
	* tap to click and two tap to right clic

## Get your terminal ready

1. Install iterm 2 <http://www.iterm2.com/>
2. Uncheck "User Lion-style Fullscreen"
3. Add ctrl + esc as hotkey to make it appear
4. Go full screen
5. Donwload the solarized theme <http://ethanschoonover.com/solarized>
6. Make it Launch on startup in the global mac os preferences
7. Make it default
8. Install oh-my-zsh : `curl -L http://install.ohmyz.sh | sh` and restart the terminal

## Get the /usr/local ownership

  sudo chown -R $USER /usr/local

> This will make you owner of your /usr/local folder. [Important for npm use.]("http://foohack.com/2010/08/intro-to-npm/#what_no_sudo")

## Install broswers

Get chrome, canary and firefox. Add some extensions to chrome :

* adblock plus
* adobe edge inspect
* advanced rest client
* ember inspector
* livereload
* markdown here
* page speed

## Install a package manager

Get homebrew :

	ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

Install a few packages :

* git
* wget
* svn
* mysql
* node
* mongo

## Install some web packages

* Install compass and sass : `gem install compass`
* Install yeoman (you will get grunt and bower) : `npm install -g yo`
* Install meteor `curl https://install.meteor.com/ | sh`

## Install source controll

Get the base git and svn. Then install source tree for Git, the github client and cornerstone for svn.

Configure your git credentials :

	git config --global user.name "fabien"
	git config --global user.email "fabien.huet@gmail.com"

> Add your new github rsa key to your bitbucket account. Your github acount will setup automatically when syncing with the github client.

## Install MAMP

Because sometimes, you will need PHP. <http://www.mamp.info/en/downloads/>

## Get your editor ready

Get sublime text : <http://www.sublimetext.com/3>, install the package control packages : <https://sublime.wbond.net/installation> and then some packages :

* advanced new file
* bracket highligther
* colorpicker
* ember snippets
* emmet
* find++
* handlebars
* html5
* javascript snippets
* jquery
* meteor snippets
* scss
* scss snipets
* sidebad enhancements
* sublime linter
* sublime linter jshint

Tweak the user settings :

	"color_scheme": "Packages/User/Monokai (SL).tmTheme",
	"font_size": 10,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_to_bracket": true,
	"scroll_past_end": true,
	"tab_size": 4,
	"translate_tabs_to_spaces": false,
	"trim_trailing_white_space_on_save": true,
	"word_wrap": "true",
	"draw_white_space": "all"


## Install other applications

### Utilities

1. **Alfred**. Big improvement to spotlight : <https://itunes.apple.com/fr/app/alfred/id405843582?mt=12>
2. **Dropbox** & **Google drive** To keep your datas safe. <https://itunes.apple.com/fr/app/xcode/id497799835?mt=12>, <https://drive.google.com>
3. **Mu torrent** You know what this is for <http://www.utorrent.com/>
4. **VLC** Best video player <http://www.videolan.org/vlc/>
5. **Moom** To arrange windows <http://manytricks.com/moom/>
6. **The unarchiver** <https://itunes.apple.com/fr/app/the-unarchiver/id425424353?mt=12>
7. **onyx** to manage mac os preferences <http://www.titanium.free.fr/downloadonyx.php>
8. **disk inventory x** <http://www.derlien.com/>
9. **Transmit** for FTP <https://panic.com/transmit/>
10. **Mou** to edit markdown <http://mouapp.com/>
11. **bartender** to manage your top task bar <http://www.macbartender.com/>
12. **caffeine** to prevent your mac from going to sleep <https://itunes.apple.com/fr/app/caffeine/id411246225?mt=12>

### Graphic / design softwares

The one I use

1. **Photoshop** & **aperture** for pictures
2. **Illustrator** to design elements
3. **Indesign** for documents
4. **Sketch** for interface
5. **Final cut** for video
6. **Audition** & **logic** for sound
7. **jpeg mini** to optimize jpeg
8. **img optim** to optimize the other images
9. **skyfont** to get google webfonts on my computer
10. **Font prep** to build font sets to inject
11. **axure** to build wireframe
12. 

### xcode

What you want is not excatly xcode. What you want is the ios devices simulator. From far the best way to preview a design on an iphone or an ipad. <https://itunes.apple.com/fr/app/xcode/id497799835?mt=12>. There are many problem you will just never encounter in chrome that you need to adress. The simulator is perfect for that.

