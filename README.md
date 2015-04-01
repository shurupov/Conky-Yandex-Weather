Conky-Yandex-Weather
====================

Conky Yandex Weather Config

To use this config for conky, you need to do next:
* Do `sudo apt-get install curl`
* Do `sudo apt-add-repository ppa:teejee2008/ppa
sudo apt-get update
sudo apt-get install conky-manager`
* Put this config somewhere.
* Change code of your city/town in "Ciy/Town" area to your city code. Example `http://export.yandex.ru/weather-ng/forecasts/28807.xml`. City codes you can find [here](https://pogoda.yandex.ru/static/cities.xml)
* Execute and set to be executed on autostart bash line `conky -c "/path/to/this/config"`
* Enjoy it


