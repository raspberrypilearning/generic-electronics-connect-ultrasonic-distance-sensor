An ultrasonic distance sensor has four pins.

![uds](images/ultrasonic-distance-sensor.png)

These pins are labelled:
- `Vcc` - This is voltage in. The sensor requires 5V.
- `Trig` - This is the trigger pin. It controls when the sensor emits ultrasound.
- `Echo` - This is the echo pin. It detects when an echo is received.
- `Gnd` - This is the ground pin.

![wiring](images/wiring-uds.png)

- The `Vcc` pin connects to the 5V pin of the Raspberry Pi
- The `Trig` pin connect to any GPIO pin of the Raspberry Pi
- The `Echo` pin needs to be connect to a potential divide, consisting of a 330Ω and 470Ω resistor, and then to a GPIO pin
- The `Gnd` pin connects to a ground pin on the Raspberry Pi
