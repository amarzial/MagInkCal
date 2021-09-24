# MagInkCal
This repo contains the code needed to drive an E-Ink Magic Calendar that uses a battery powered (PiSugar2) Raspberry Pi Zero WH to retrieve events from a Google Calendar, format it into the desired layout, before pushing it to a Waveshare 12.48" tri-color E-Ink display. Note that the code has only been tested on the specific hardware mentioned, and customization of the code is necessary for it to work with other E-Ink displays or Battery/RTC add-ons. That said, enjoy working on your project and hopefully this helps to jump-start your magic calendar journey.

## Background
Back in 2019, I [started a thread in Reddit](https://www.reddit.com/r/RASPBERRY_PI_PROJECTS/comments/dzveio/seeking_advice_on_wallmounted_battery_powered/) to bounce an idea I had with the community: to replicate the [Android Magic Calendar concept](https://www.youtube.com/watch?v=2KDkFgOHZ5I) that inspired many DIY projects in the years that followed. But specifically, I wanted it to run on battery so I could position it anywhere in house, and even hang it on the wall without a wire dangling beneath it. I also wanted the parts to be plug and play since I have neither the desire nor the steady hands needed to solder anything. After sitting on that idea for close to a year, I finally got my act together to order the parts I needed for this project. I [posted another update to Reddit in 2020](https://www.reddit.com/r/raspberry_pi/comments/k1hm7a/work_in_progress_1248_eink_magic_calendar_details/), but got overwhelmed with life/work so it took me almost another year before posting the full set of instructions and code here.

## Hardware Required
- [Raspberry Pi Zero WH](https://www.raspberrypi.org/blog/zero-wh/) - Header pins are needed to connect to the E-Ink display
- [Waveshare 12.48" Tri-color E-Ink Display](https://www.waveshare.com/product/12.48inch-e-paper-module-b.htm)
- [PiSugar2 for Raspberry Pi Zero](https://www.pisugar.com/) ([Tindie](https://www.tindie.com/products/pisugar/pisugar2-battery-for-raspberry-pi-zero/))
