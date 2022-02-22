# Seeed_reTerminal_Bridge_RS485_exmaple

![](https://files.seeedstudio.com/wiki/reTerminal_Bridge/reTerminal_bridge.jpg)

Example Python code for using RS485 on reTerminal Bridge.

Since the RS485 function uses ttyS0, it is necessary to close the ttyS0 system interaction function before starting.

```sh
$ sudo raspi-config
```

Select **Interface Options**, **Serial port** in turn. 
On the next screen you will be prompted if you want to login shell accessible over serial, select **No**. 
Then in “Do you want to use serial port hardware”, make sure **Yes** is selected with. 
After reTerminal has made changes, you will see the following text appear on the screen. 

Use a cable to connect the reTerminal Bridge to the computer via the RS485 interface.

Open the serial port software on the computer. Execute the command `sudo python3 rs485.py` to get the following effects. 

At the same time, you can also send 16-byte data to reTerminal through the serial port assistant within 5 seconds of receiving the message.

## Getting Started

- [reTerminal Bridge wiki]()


