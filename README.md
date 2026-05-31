MorseDX supports BLE (Bluetooth Low Energy) CW Morse keyer connections for wireless Morse code learning and practice.

You can connect via Bluetooth and practice CW training between any Mac running the MorseDX application or any iOS device running the MorseUs application.

MorseDX supports Bluetooth connectivity for receiving BLE iambic paddle signals (with ESP32-based devices).

It also supports Morse paddles connected through USB TTL, USB FTDI, USB UART, and USB Serial interfaces (Arduino, etc.).

MorseDX includes a real-time FFT decoder that converts Morse audio tones into letters. A controllable sliding graphic display shows dits and dahs in real time.

In Graphic Mode, you can enable the Paddle Draw option to visualize iambic or straight paddle touches alongside the dit/dah graphics.
If no paddle input is detected, the graphic animation pauses after a short delay to save power.

With the Practice feature, you can practice sending letters and words using:

* Mixed text generated from entered characters
* 4300 built-in common English words
* 1450 Turkish words (depending on system language)

At the end of each practice session, achievement statistics are displayed.

With the Listen Groups feature, you can practice Morse listening using selected groups of letters and words.

The Q button displays a list of standard Q codes.

Advanced Keyer Controls

* Tone
* WPM speed
* Character spacing
* Iambic paddle mode (Type A / Type B)
* Paddle swap
* Keyer weight

QRM Training Feature

The QRM feature adds background noise for realistic CW practice.
You can adjust the QRM volume independently without affecting the CW audio volume.

If the BleTX option is enabled, you can send direct text messages to another connected device using the Send button.

If you type “show help” and press ENTER, MorseDX will display the ESP32 programming guide, including Arduino example code and wiring diagrams for your wireless Morse CW paddle.

Additional wireless BLE keyer code examples and documentation are available on:

Bluetooth iambic CW Paddle Morse Keyer TX only GitHub Repository
