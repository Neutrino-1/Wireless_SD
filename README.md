# Wireless_SD

A normal micro SD to SD adapter is converted into a wireless Card reader using esp12E with FTP support.
Files can be transferred to SD and also files can be copied from SD to any device where you can run an FTP client.
For this particular project I used the AndFTP client for Android and the same process can be followed in PC by using WinSCP.

![Wireless SD final build](https://github.com/Neutrino-1/Wireless_SD/blob/master/Circuit/wireless%20SD%20another.jpg)

### Getting Started

Open **Wireless_SD.ino** with arduino IDE [Tested on Arudino IDE 1.8.12 above]
all the other files will open along with it.

### Prerequisites

* [ESP-Core](https://github.com/esp8266/Arduino) - by Ivan Grokhotkov

### Usage

Once the device is powered up follow the below steps to transfer data from SD card:
```
-> Connect to the acess point named "SD Reader" with the password "ASDF@123".

-> download any FTP client application (Android - AndFTP, Windows - WinScp).

-> Host name "192.168.12.7" Port "21".

-> Enter the user name and password as "esp8266".

-> Connect to the server
```

## License

This project is licensed under the GNU License - see the [LICENSE.md](https://github.com/Neutrino-1/Wireless_SD/blob/master/LICENSE) file for details

## Acknowledgments

* [David Paiva](https://github.com/nailbuster) Ported Arduino FTP server to esp8266/esp32.

## Support

<a href="https://www.buymeacoffee.com/Neutrino"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=Neutrino&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"></a>
