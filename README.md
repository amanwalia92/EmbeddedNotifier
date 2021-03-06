# EmbeddedNotifier
With this project realms of social media with embedded systems are connected. Our present project offers a proof of concept that with IOT (Internet of Things) going popular we can connect very small embedded devices used in our day to day lives to social media through internet. This offers us smart devices which can use data generated by users on various web platforms to perform meaningful and intelligent tasks.
![Alt text](EmbeddedNotifier.png?raw=true "Project")
## Getting Started
Download or clone this repository to your local Raspberry File System.Connect LCD module to Raspberry pi.

### Prerequisites

You need to have installed GMail and Facebook python SDKs on Raspberry Pi.This can be done using
```
sudo pip install gmail
sudo apt-get install python-facebook 
```

### Installing
Download this project to your machine.
Move to the folder using
```
cd EmbeddedNotifier
```
And compile oAuthorize.c using
```
gcc -o oAuthorize oAuthorize.c
```
Run this using 
```
./oAuthorize
```
Provide the respective details.
Then run main project using 
```
sudo python util_module.py
```
### Demo
Watch this [Video](Demo.mkv) to see how it works.

## Authors

* **Amanpreet Walia** - *Implemented Facebook Sync and Hardware Configuration* 
* **Gabriel Loja** - *Implemented Gmail Sync and oAuthorize* 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
