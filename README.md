<h1 align="center">
Wifi Password
</h1>
<p align="center">
Quickly fetch your WiFi password and if needed, generate a QR code of your WiFi to allow phones to easily connect.
<br>
Works on <b>macOS</b> and <b>Linux</b>, <b>Windows</b>
<img src="images/demo.gif" align="center">
</p>

## Installation

### Install using `pip`
```console
$ python3 -m pip install --user wifi-password
```

### Install using `git`
```
> Git Clone
> Change Directory
> python3 setup.py install
```


## Usage
```console
$ wifi-password --help
usage: wifi_password [options]

optional arguments:
  -h, --help            show this help message and exit
  --show-qr, -show      Show a ASCII QR code onto the terminal/console
  --save-qr [PATH], -save [PATH]
                        Create the QR code and save it as an image
  --ssid SSID, -s SSID  Specify a SSID that you have previously connected to
  --version             Show version number
```

## Reference
- This project is an improvement of [wifi-password](https://github.com/rauchg/wifi-password) created by [@rauchg](https://github.com/rauchg), where I have added support for multiple platforms and have added the feature for generating QR codes.