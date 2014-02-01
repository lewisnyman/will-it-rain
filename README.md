## Should I bring an umbrella?
http://sebastiannilsson.com/en/blogg/will-it-rain/

Living in Göteborg, Sweden means that many mornings you ask yourself the question "do I need an umbrella today?". To outsource more small decisions to computers I programmed a microprocessor that respond with activating a led if an umbrella is recommended.

![Spark Core as Umbrella reminder](http://sebastiannilsson.com/wp-content/uploads/2014/01/2014-01-06-11.11.08-300x224.jpg)

The idea is very simple. The microprocessor reads the weather forecast from forecast.io for the next 10 hours (which is about the time I expect to be away from home). If any of these hours include rain (more than a few mm) then light the led. Unlit led obviously means no rain.

### How it works

#### Hardware
Spark Core
Breadboard
Light Emitting Diode
Resistor
Usb cable for power supply

#### Weather forecast using the Forecast.io API

WIP

#### Code on the microprocessor

Spark Core is a microprocessor that connects to Wifi. You upload your code to it over their cloud service.

Get a Spark Core or similar and connect it to wifi.
Copy my code for the Spark Core. The only needed change is the variable for the url.
Upload
