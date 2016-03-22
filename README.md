#tmux
sudo apt-get install -y python-software-properties software-properties-common 
sudo add-apt-repository -y ppa:pi-rho/dev                                    
sudo apt-get install -y tmux=2.0-1~ppa1~t
git clone git@github.com:p-tricky/tmux-config.git .tmux
ln -s .tmux.conf .tmux/tmux.conf
cd .tmux 
git submodule update --init --recursive
<prefix> I

