# archup
My Arch Linux setup script

# Setup
    
    pacman -S python python-pip git openssh
    pip install cdist
    systemctl enable sshd.socket
    git clone https://github.com/zhaostu/archup.git

# Usage

    cdist config -c conf localhost
