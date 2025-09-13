# Home Assistant plugin for Macro Deck 2
Control your Home Assistant smart home with Macro Deck!

# Features
- ### Call service
Create buttons to call services of Home Assistant like "light.toggle"
- ### Variables
Select entities you want to use as a variable in Macro Deck to indicate a state or show a temperature on a action button

### This is a plugin for [Macro Deck 2](https://github.com/SuchByte/Macro-Deck), it does NOT function as a standalone app
<img height="64px" src="https://macrodeck.org/images/macro_deck_2_official_plugin.png" />

# How to configure

- Head over to <your-home-assistant-ip:port/profile/security> i.e 192.168.1.10:8123/profile/security;
or navigate to Profile (Your icon on the bottom of the page) then to Security
- At the bottom of the page you will find "Long-lived access tokens"
- Select "Create"
- Add a name of your preference, i.e Macro Pad Plugin
- Copy the Token

- On the Macro pad app, after installing the plugin, select "Configure"
- Under "Host" input your Home Assistant IP Server IP address i.e 192.168.1.10:8123
- Under "Token" paste the token you copied previously
- Select OK

Configuration is successful!

# Third party licenses
This plugin uses some awesome 3rd party libraries:
- [Newtonsoft.Json (MIT license)](https://www.newtonsoft.com/json)
- [WatsonWebsocket (MIT license)](https://github.com/jchristn/WatsonWebsocket)
