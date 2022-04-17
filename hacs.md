## Home Assistant Community Store | <a href="https://hacs.xyz/">HACS</a>
<img src="https://assets.hacs.xyz/logo.svg" width="180px" height="160px"/>

> Download 

  <a href="https://github.com/hacs/get">Download HACS Scripts to setup HACS</a>

> Requirements

  * <a href="https://www.home-assistant.io/">Home Assistant</a> version <a href="https://my.home-assistant.io/redirect/info">2022.3.0</a> or newer.
  * A <a href="https://github.com/home-assistant/architecture/blob/master/adr/0012-define-supported-installation-method.md">supported</a> Home Assistant installation.
  * Access to the filesystem where the Home Assistant configuration files are located.
  * Know how to access the Home Assistant log file.
  * stable internet connection with sufficient available data

> Follow Up Steps

  * Go to the <a href="https://my.home-assistant.io/redirect/supervisor_store/">Add-on store</a>
  * Install <a href="http://homeassistant.local:8123/hassio/addon/core_ssh/info"><img src="https://github.com/home-assistant/addons/blob/master/ssh/icon.png" width="25px" height="25px"/> Terminal & SSH </a> | <a href="https://github.com/home-assistant/hassio-addons/tree/master/ssh">github</a>
    * Install one of the <a href="">SSH add-ons</a> (you need to enable advanced mode in your user profile to see them) 
    * Configure the SSH add-on you chose by following the documentation for it
    * Start the SSH add-on
  * Connect to the SSH add-on
  * Run the HACS download script

  
        wget -O - https://get.hacs.xyz | bash -

       
    > Troubleshooting

  * CTRL+V not working for you?
    * Try CTRL+SHIFT+V instead
    * Try SHIFT+INS(insert) instead
    * Try Right-click instead
  * Having issues accessing https://get.hacs.xyz in the terminal?
    * Try it with https://raw.githubusercontent.com/hacs/get/main/get instead
