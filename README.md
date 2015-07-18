# lsr
Pretty ls with ruby

## Features

Easy to read permissions split by group, gradient colored sizes and times. 

Supports standard ls options with the addition of -P to hide permissions in a long list.

## Installation

Clone repo and place lsr somewhere in your path.

    mkdir bin src
    git clone https://github.com/zsoltf/lsr.git src/lsr
    cd !$
    vim lsr  # inspect unknown files from the internets
    cp lsr ~/bin
    echo 'export PATH:$PATH:$HOME/bin' >> ~/.bashrc

## Screenshots
### Long Listing
![lsr -l](https://github.com/zsoltf/lsr/wiki/images/lsrl.png)

### Sort by Time
![lsr -lt](https://github.com/zsoltf/lsr/wiki/images/lsrlt.png)

### Sort by Size
![lsr -lS](https://github.com/zsoltf/lsr/wiki/images/lsrls.png)
