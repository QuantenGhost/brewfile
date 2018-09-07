# Brewfile
#
# Maintained by ByungjinPark <posquit0.bj@gmail.com>
# http://www.posquit0.com/


cask_args appdir: '/Applications'

### System {{{
  ## System Libraries
  # Manage compile and link flags for libraries
  brew 'pkg-config'
  # Text-based UI library
  brew 'ncurses'
  # GNU internationalization (i18n) and localization (l10n) library
  brew 'gettext'
  # Library for command-line editing
  brew 'readline'
  # GNU multiple precision arithmetic library
  brew 'gmp'
  # Collection of portable C++ source libraries
  brew 'boost'
  # Image manipulation library
  brew 'jpeg'
  # Library for manipulating PNG images
  brew 'libpng'
  # TIFF library and utilities
  brew 'libtiff'

  ## Mac OS X
  # Homebrew GUI App for OS X
  cask 'cakebrew'
  # Mac App Store command line interface
  brew 'mas'
  # Swiss Army Knife for macOS
  brew 'm-cli'

  ## Monitoring
  brew 'htop', args: ['with-ncurses']
  # Display an interface's bandwidth usage
  brew 'iftop'
  # Top-like interface for container metrics
  brew 'ctop'
### }}}


### File System {{{
  ## Cloud
  cask 'google-drive-file-stream'

  ## Recovery
  # Console program to recover files based on their headers and footers
  brew 'foremost'
### }}}

### Web {{{
  ## Web Browser
  cask 'google-chrome'
  cask 'firefox-developer-edition'

  ## Flash Player for Web Browser
  # Adobe Flash Player NPAPI (plugin for Safari and Firefox)
  cask 'flash-npapi'
  # Adobe Flash Player PPAPI (plugin for Opera and Chromium)
  cask 'flash-ppapi'

  ## HTTP Request
  # Powerful HTTP and GraphQL tool belt
  cask 'insomnia'
  # API Development Environment
  cask 'postman'
### }}}


### Media {{{
  ## Video
  # VLC media player
  cask 'vlc'
  # Home theater/media center software and entertainment hub for digital media
  cask 'kodi'

  ## Image
  # Streamlined and convenient image viewer and browser
  cask 'xee'
  # Perl lib for reading and writing EXIF metadata
  brew 'exiftool'
### }}}


### Messaging {{{
  cask 'slack'
  cask 'telegram'
  cask 'skype'
### }}}


### Network {{{
  ## Analysis
  # The world’s foremost and widely-used network protocol analyzer
  cask 'wireshark'
  # Port scanning utility for large networks
  brew 'nmap'

  ## Proxy & VPN
  # Free software for OpenVPN on OS X
  cask 'tunnelblick'
### }}}


### Utility {{{
  ## Compress/Uncompress
  # 7-Zip (high compression file archiver) implementation
  brew 'p7zip'
  # General-purpose data compression with high compression ratio
  brew 'xz'
### }}}


### Game {{{
  ## Emulator
  cask 'openemu'
### }}}


### Programming Language {{{
  ## Node.js
  # Platform built on V8 to build network applications
  brew 'node'
  # Alternative JavaScript package manager by Facebook
  brew 'yarn'

  ## Python
  # Python3
  brew 'python'
  # Python2
  brew 'python@2'

  ## Golang
  # Open source programming language to build simple/reliable/efficient software
  brew 'go'
  # Go cross compile tool
  brew 'gox'

  ## Java
  # Java Standard Edition Development Kit 8
  # INFO: Need to reboot
  cask 'java8'
  # Java build tool
  brew 'ant'
  # Java-based project management
  brew 'maven'

  ## Scala
  # JVM-based programming language
  brew 'scala', args: ['with-docs', 'with-src']
  # Build tool for Scala projects
  brew 'sbt'

  ## C Family
  # GNU compiler collection
  brew 'gcc'

  ## Shellscript
  # Static analysis and lint tool, for (ba)sh scripts
  brew 'shellcheck'

  ## Lua
  # Powerful, lightweight programming language
  brew 'lua'
  # Just-In-Time Compiler (JIT) for the Lua programming language
  brew 'luajit'
  # Package manager for the Lua programming language
  brew 'luarocks'

  ## Haskell
  # Glorious Glasgow Haskell Compilation System
  brew 'ghc'

  ## Ruby
  # Powerful, clean, object-oriented scripting language
  brew 'ruby'

  ## Verilog
  # Verilog simulation and synthesis tool
  brew 'icarus-verilog'
### }}}


### Device {{{
  ## Android
  # Android SDK Platform-Tools
  cask 'android-platform-tools'
  # Android File Transfer
  cask 'android-file-transfer'
### }}}


### VCS {{{
  ## Git & GitHub
  # Distributed revision control system
  brew 'git'
  # Small git utilities
  brew 'git-extras'
  # Extensions to follow Vincent Driessen's branching model
  brew 'git-flow'
  # Prevents you from committing sensitive information to a git repo
  brew 'git-secrets'
  # Text interface for Git repositories
  brew 'tig'
  # OS X status bar application for Github
  cask 'gitee'
  # Extend your GitHub workflow beyond your browser <Paste>
  cask 'github'
  # The legendary Git GUI client
  cask 'gitkraken'

  ## Mercurial
  # Scalable distributed version control system
  brew 'mercurial'
### }}}


### Code Editor & IDE {{{
  ## Editor: Vim
  # Vi 'workalike' with many additional features
  brew 'vim', args: ['with-gettext', 'with-lua', 'with-luajit', 'with-tcl']
  # GUI for vim, made for macOS
  cask 'macvim'
  # Ambitious Vim-fork focused on extensibility and agility
  brew 'neovim'

  ## Editor: Microsoft Visual Studio Code
  cask 'visual-studio-code'

  ## IDE
  # JetBrain
  cask 'webstorm'
  cask 'intellij-idea'
### }}}


### Terminal {{{
  ## Terminal Emulator
  # Terminal Emulator for macOS
  cask 'iterm2'

  ## Utility
  # Opens a terminal window to the current directory in Finder
  # INFO: Need to set up manually
  cask 'go2shell'

  ## Shell: Bash
  # Bourne-Again SHell, a UNIX command interpreter
  brew 'bash'
  # Programmable completion for Bash 4.1+
  brew 'bash-completion@2'

  ## Shell: Fish
  # User-friendly command-line shell for UNIX-like operating systems
  # INFO: Need to add `/usr/local/bin/fish` to `/etc/shells`
  brew 'fish'

  ## Shell: Zsh
  # UNIX shell (command interpreter)
  # INFO: Need to add `/usr/local/bin/zsh` to `/etc/shells`
  brew 'zsh', args: ['with-gdbm', 'with-pcre']
#}}}


### Database {{{
  ## SQL
  cask 'datagrip'

  ## Key-Value DB
  # Persistent key-value database, with built-in net interface
  brew 'redis'

  ## LDAP
  # The Eclipse-based LDAP browser and directory client
  cask 'apache-directory-studio'
### }}}


### Virtualization {{{
  ## Virtual Machine
  # Oracle VirtualBox
  # INFO: Need to enable their kernel extension
  cask 'virtualbox'

  ## Container
  # Docker Community Edition for Mac (Edge)
  cask 'docker-edge'
### }}}


### Development {{{
  # Cross-platform make
  brew 'cmake'
  # Generic library support script
  # INFO: In order to prevent conflicts with Apple's own libtool we have prepended a "g"
  brew 'libtool'
### }}}


### DevOps {{{
  # Tool to build, change, and version infrastructure
  brew 'terraform'

  # Tool for building and managing virtual machine environments
  cask 'vagrant'
  # Manage your vagrant machines in one place
  cask 'vagrant-manager'

  # Tool for creating identical machine images for multiple platforms
  brew 'packer'
  # Automate deployment, configuration, and upgrading
  brew 'ansible'
### }}}

### Cryptography {{{
  # SSL/TLS cryptography library
  brew 'openssl'
  # Enhanced version of john, a UNIX password cracker
  brew 'john-jumbo'
  # Suite of barcodes-reading tools
  brew 'zbar'
### }}}

### Font {{{
  # XML-based font configuration API for X Windows
  brew 'fontconfig'

  ## Font Family: Icons
  # Most popular icon toolkit
  cask 'caskroom/fonts/font-fontawesome'
  # Simple and Minimal Line Icons
  cask 'caskroom/fonts/font-simple-line-icons'
  # Material Design icons by Google
  cask 'caskroom/fonts/font-material-icons'
  # An iconic font made for developers
  cask 'caskroom/fonts/font-devicons'
  # WordPress admin icon font
  cask 'caskroom/fonts/font-dashicons'

  ## Font Family: Nanum
  cask 'caskroom/fonts/font-nanumgothic'
  cask 'caskroom/fonts/font-nanumgothiccoding'
  cask 'caskroom/fonts/font-nanummyeongjo'

  ## Font Family: Powerline
  cask 'caskroom/fonts/font-anonymice-powerline'
  cask 'caskroom/fonts/font-consolas-for-powerline'
  cask 'caskroom/fonts/font-dejavu-sans-mono-for-powerline'
  cask 'caskroom/fonts/font-droid-sans-mono-for-powerline'
  cask 'caskroom/fonts/font-fira-mono-for-powerline'
  cask 'caskroom/fonts/font-inconsolata-for-powerline'
  cask 'caskroom/fonts/font-liberation-mono-for-powerline'
  cask 'caskroom/fonts/font-menlo-for-powerline'
  cask 'caskroom/fonts/font-meslo-for-powerline'
  cask 'caskroom/fonts/font-monofur-for-powerline'
  cask 'caskroom/fonts/font-noto-mono-for-powerline'
  cask 'caskroom/fonts/font-roboto-mono-for-powerline'
  cask 'caskroom/fonts/font-source-code-pro-for-powerline'
  cask 'caskroom/fonts/font-ubuntu-mono-derivative-powerline'
### }}}
