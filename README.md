# Bitron-HA
Bitron Doorbell in Home Assistant.

The intercom is powered by a 17V audio signal, which is generated with the help of a tone generator in the door speaker.

A level converter is needed to isolate the 17V from the 3.3V GPIO.

## Phone:
The Circuit is under the Wemos Board.

![image](https://github.com/Gamer08YT/Bitron-HA/assets/31771657/a06fe9be-ba74-4ada-ae5c-a5b7cbf23d8f)

## Circuit:
Please use not Linear Voltage Regulator, it consumes too much energy and is inefficient, I later used a Buck Converter.
![image](https://github.com/Gamer08YT/Bitron-HA/assets/31771657/6b753a1b-5900-42e2-b213-8a6084dac13a)

## Electronic Bell Signal:
![image](https://github.com/Gamer08YT/Bitron-HA/assets/31771657/96e70948-ba1d-422c-b5eb-39a9d1180ad7)


### Possible to-dos:
- Tap voice connection
- Recorded voice messages
