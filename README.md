# lsr
Pretty ls with ruby

## Features

Easy to read permissions split by group, gradient colored sizes and times. 

Supports standard ls options with the addition of -P to hide permissions in a long list.

## Installation

Clone repo and place lsr somewhere in your path.

    git clone https://github.com/zsoltf/lsr.git
    # inspect unknown files before running them
    vim lsr/lsr  
    # copy the script to your local bin
    cp lsr/lsr ~/bin
    # in case ~/bin is not in the path or doesn't exist
    mkdir ~/bin
    echo 'export PATH:$PATH:$HOME/bin' >> ~/.bashrc

## Screenshots
### Long Listing
![lsr -l](https://github.com/zsoltf/lsr/wiki/images/lsrl.png)

### Sort by Time
![lsr -lt](https://github.com/zsoltf/lsr/wiki/images/lsrlt.png)

### Sort by Size
![lsr -lS](https://github.com/zsoltf/lsr/wiki/images/lsrls.png)
