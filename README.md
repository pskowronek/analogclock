[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
# Lovelace Analog Clock
An analog clock card for Home Assistant Lovelace. Colors are fully customizable, weekday names and date formats are localizable.


![Analog clock2](https://github.com/tomasrudh/analogclock/blob/main/Images/AnalogClock2.png?raw=true)

| Name | Type | Default | Description
| --- | --- | --- | --- |
| locale | String | HA setting | Locale for date and week day |
| diameter | Integer | Automatic | Diameter of the clock |
| hide_SecondHand | Boolean | false | If true, the second hand is hidden |
| hide_WeekNumber | Boolean | false | If true, the week number is hidden |
| hide_WeekDay | Boolean | false | If true, the week day is hidden |
| hide_Date | Boolean | false | If true, the date is hidden |
| hide_FaceDigits | Boolean | false | If true, the hour numbers are hidden |
| hide_DigitalTime | Boolean | false | If true, the digital time hidden |
| color_Background | String | primary background color | Background color of the clock |
| color_Ticks | String | Silver | Color of the border ticks |
| color_FaceDigits | String | Silver | Color of the borde digits |
| color_DigitalTime | String | #CCCCCC | Color of the digital time |
| color_HourHand | String | #CCCCCC | Color of the hour hand |
| color_MinuteHand | String | #EEEEEE | Color of the minute hand |
| color_SecondHand | String | Silver | Color of the second hand |
| color_Text | String | Silver | Color of texts |

![Analog clock3](https://github.com/tomasrudh/analogclock/blob/main/Images/AnalogClock3.png?raw=true)

```
- type: "custom:analog-clock"
  hide_SecondHand: true
  locale: sv-SE
  diameter: 200
  color_HourHand: "#326ba8"
  color_MinuteHand: "#3273a8"
  color_DigitalTime: "#CCCCCC"
  color_FaceDigits: "#a83832"
  color_Ticks: "Silver"
```
<a href="https://www.buymeacoffee.com/rudhan" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
