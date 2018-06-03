# upcycling-interactive-humidifier
Let's make upcycling interactive humidifier with legacy humidifier and openHW

# SW upcycling
## Reuse Adafruit DHT unified sensor library sample.
## Reuse Adafruit Neopixel library sample.

# HW upcycling
## Reuse a legacy humidifier 
![legacy humidifier](/media/legacy_humidifier.png)

# HOWTO

## 1. Upload combined upcycling-interactive-humidifier.ino to Arduino Nano.
![upload upcycling interactive humidifier ino](/media/upload_upcycling_interactive_humidifier_ino.png)
## 2. Install neopixel strip to wall for humidity state notice with ambient color.

## 3. Install DHT11 sensor to wall for gathering humidity.

## 4. Connect Realy Multi Tap to legacy humidifier for interactive control.
![relay multi tap](/media/relay_multi_tap.png)

## 5. Connect external 5V DC power supply for LED control.

## 6. Attach Home Humidity Board
- In our home, first daughter drew it after understood 5 level meaning.

![home humidity board](/media/home_humidity_board.png)

### Ambient Color Notice
- Humidity <= 20% : Red Color

- 20% < Humidity <= 40% : Yellow Color

- 40% < Humidity <= 60% : Green Color

- 60% < Humidity <= 80% : Cyan Color

- 80% < Humidity : Blue Color

### Humidifier Relay Control
- Humidity <= 50% : Turn On Humidifier

- Humidity > 50% : Turn Off Humidifier

![humidity red state](/media/humidity_red_state.png)
![humidity yellow state](/media/humidity_yellow_state.png)
![humidity green state](/media/humidity_green_state.png)
![humidity cyan state](/media/humidity_cyan_state.png)
![humidity blue state](/media/humidity_blue_state.png)

## 7. Now transform legacy humidifier to interactive humidifier
- Just check water tank of humidifier sometimes whether it's empty or not. :)

![final installation](/media/final_installation.png)
