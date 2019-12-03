#Chinese Pinyin input method for Ubuntu 16.04  

1. System Settings->Language Support->Install/Remove Languages, Install Chinese  
2. input the command:  
    ``` shell
    sudo apt-get install ibus ibus-clutter ibus-gtk ibus-gtk3 ibus-qt4
    im-config -s ibus
    sudo apt-get install ibus-pinyin
    reboot
    ibus-setup
    ```
3. add "chinese-pinyini" in "input method" table
4. System Settings->Text Entry, add chinese pinyin method
5. `ibus-daemon -drx`


