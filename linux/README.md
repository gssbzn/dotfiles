sudo apt-get update && sudo apt-get upgrade
sudo add-apt-repository ppa:gnome3-team/gnome3
sudo add-apt-repository ppa:gnome3-team/gnome3-next
sudo add-apt-repository ppa:webupd8team/gnome3
sudo add-apt-repository ppa:moka/faba-icon-theme
sudo add-apt-repository ppa:webupd8team/java
sudo add-apt-repository ppa:moka/stable
sudo apt-get update
sudo apt-get dist-upgrade
sudo apt-get install aptitude tasksel debtags tagcoll aptitude-doc aptitude-doc-en aptitude-doc-es synaptic
sudo aptitude install rar unrar vlc ubuntu-restricted-extras msttcorefonts build-essential aspell-es lm-sensors gksu thermald cpufrequtils linux-tools-common linux-tools-generic sensord htop skype gnome-shell gnome-sushi gnome-contacts gnome-shell-extensions-user-theme gnome-tweak-tool samba samba-tools system-config-samba smbfs ntp  ssh curl git git-core git-flow subversion autoconf automake libfcgi-dev libreadline6 libreadline6-dev zlib1g zlib1g-dev openssl libssl-dev libyaml-dev ncurses-dev libyaml-dev libxml2-dev libxslt-dev libc6-dev sqlite3 libsqlite3-0 libsqlite3-dev  libtool bison libcwidget-dev libhtml-parser-perl libhtml-template-perl libxml-simple-perl folks-common libfolks-eds25 lzma xz-lzma faba-icon-theme faba-icon-theme-symbolic faba-mono-icons faba-colors faba-mono-icons faba-colors oracle-java8-installer binfmt-support visualvm ttf-baekmuk ttf-unfonts ttf-unfonts-core java-openjdk tzconfig tzdata postgresql libpq-dev zsh
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh
chsh -s `which zsh`
