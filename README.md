# RAK4631 Weather Monitoring - WisBlock Kit 1

- [RAK4631 Weather Monitoring - WisBlock Kit 1](#rak4631-weather-monitoring---wisblock-kit-1)
  - [Architecture](#architecture)
  - [Power consumption without Power Saving (Semaphore)](#power-consumption-without-power-saving-semaphore)
    - [Battery Capacity](#battery-capacity)
    - [Power Consumption](#power-consumption)
  - [Power consumption with Power Saving mode](#power-consumption-with-power-saving-mode)
  - [LPP Cayenne Format](#lpp-cayenne-format)
  - [Helium JavaScript Decoder Function](#helium-javascript-decoder-function)
  - [OpenWeather](#openweather)
  - [Ubidots](#ubidots)
  - [MyDevices Cayenne](#mydevices-cayenne)
 

## Architecture

![architecture](./docs/gallery/Architecture.png)

## Power consumption without Power Saving (Semaphore)

![RAK4631](./docs/gallery/Battery_Voltage_Without_Power_Saving.png)

### Battery Capacity

- Battery Samsung INR18650-32E 3100mAh - 6.4A - 18650 - Li-ion

### Power Consumption 

- 6.3 mA at rest  
- Peak at 72 mA when sending data over LoRaWan protocol
- The module drained the current of 4.03 Volts to 3.66 Volts in seven days

## Power consumption with Power Saving mode

## LPP Cayenne Format

## Helium JavaScript Decoder Function

[JavaScript Decoder Function](https://gist.github.com/vhuynen/4147d0d65edb16d525ade26eb0dfb34a)

## OpenWeather

## Ubidots

[Connect Helium with Ubidots](https://help.ubidots.com/en/articles/5008195-plugins-connect-helium-with-ubidots)

![RAK4631 Dashboard with Ubidots](./docs/gallery/ubidots.png)

## MyDevices Cayenne

[Connect Helium with MyDevices Cayenne](https://docs.helium.com/use-the-network/console/integrations/mydevices-cayenne/)

![RAK4631 Dashboard with My Devices Cayenne](./docs/gallery/my_devices_cayenne.png)
