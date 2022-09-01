# bcc

Battery Charging Controller for Termux. Keeps battery charge between 65% to 75% when plugged in 24/7. Only works on Xperia M with Magisk rooted lineage-14.1-20180622-UNOFFICIAL-nicki for now.

## Prerequisites

- root
- Termux:Boot
- screen

## Install

1. Copy [bcc](bcc) and [.termux](.termux) directory including their contents to `/data/data/com.termux/files/home`.

    ```
    /data/data/com.termux/files/home/bcc/bcc
    /data/data/com.termux/files/home/.termux/boot/10-bcc
    ```

2. Make executable.

    ```
    $ chmod +x /data/data/com.termux/files/home/bcc/bcc
    $ chmod +x /data/data/com.termux/files/home/.termux/boot/10-bcc
    ```
    
3. If installed correctly, `bcc` will start on boot on a `screen` session.
