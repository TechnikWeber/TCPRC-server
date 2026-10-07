> **Deprecated:** This repository is no longer maintained. Please use [YonderRC](https://github.com/TechnikWeber/YonderRC) instead.

Preparations:

Flash Bookworm, enable SSH.

sudo raspi-config
enable i2c

sudo apt-get update
sudo apt-get upgrade

sudo apt install python3-pip
sudo pip3 install adafruit-circuitpython-pca9685 --break-system-packages
sudo pip3 install adafruit-circuitpython-servokit --break-system-packages

//sudo pip3 install adafruit-pca9685 --break-system-packages (not neeed? i didnt install ist)

## License

[MIT](LICENSE).
