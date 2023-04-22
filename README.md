# Endeavour-Cheats
I will be dropping CLI prompts and useful scripts here

installing bcml

#get yay
sudo pacman -S git base-devel
#or check for it using pacman -Q base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
#or use endeavour and get yay pre-installed :P

#install python39
pacman -S python39

#create python39 virtual environment
python3.9 -m venv ~/.local/bcml_env
#to start venv (you always have to do this if running bcml)
source ~/.local/bcml_env/bin/activate
#install
python3.9 -m pip install bcml
#run
bcml
