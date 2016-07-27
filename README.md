# archup
My Arch Linux setup script


# Requirement
* A fresh install of Arch Linux
* cdist >= 4.2.0

# Setup
    
    # pacman -S python python-pip git openssh
    # pip install cdist
    # systemctl enable sshd.socket
    $ git clone https://github.com/zhaostu/archup.git

# Usage

    cdist config -c conf localhost
