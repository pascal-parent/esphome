# Home Assistant Weather Dashboard for my weather station

*** Actively being developed!***

The first column is the forecast, the second is the data from the weather station and the third the interior data.

![Dashboard](../Images/HAWeatherDashboard.png)

You can find the current yaml file [here](ha_weather_dashboard.yaml)
 
You will need the following Frontend elements from HACS:
- [ApexCharts Card](https://github.com/RomRider/apexcharts-card)
- [button-card](https://github.com/custom-cards/button-card)
- [Canary](https://github.com/jcwillox/lovelace-canary)
- [Clock Weather Card](https://github.com/pkissling/clock-weather-card)
- [Flexible Horseshoe Card](https://github.com/AmoebeLabs/flex-horseshoe-card)
- [Horizon Card](https://github.com/rejuvenate/lovelace-horizon-card)
- [Hourly Weather Card](https://github.com/decompil3d/lovelace-hourly-weather)
- [layout-card](https://github.com/thomasloven/lovelace-layout-card)
- [Lightning Detector Card](https://github.com/ironsheep/lovelace-lightning-detector-card) (Future)
- [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
- [Animated Weather Card](https://github.com/bramkragten/weather-card)

And the [Minimalist theme](https://github.com/UI-Lovelace-Minimalist/UI).

To get the maximum and minimum sensors for the dashboard, you will need this [custom component](https://github.com/philsson/HomeAssistantCustomComponents) by philsson.

The rest of the custom components are in the [ESPHome yaml](../ESPHome/weather_station.yaml) and compiled to the weather station micro-controller.

## History

- 2023-08-04 First beta commit.
- 2023-08-28 Updated dashboard to include horseshoe meters and cleaned up some cards
- 2023-08-29 Added the custom sensor yaml 

## Sponsoring

 If you like my work and want to support the growth of the project, you can! 

[![Buy Me A Coffee][2]][1]

[1]: https://www.buymeacoffee.com/parentpj
[2]: https://cdn.buymeacoffee.com/buttons/default-black.png