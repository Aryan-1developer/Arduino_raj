# Arduino_raj
I am learning Arduino at the moment and here i will show what i have learned so far.


Ultrasonic Distance Sensor with I2C LCD

This Arduino project measures distance using an ultrasonic sensor and displays the result on an I2C-enabled LCD screen. It's ideal for beginners exploring sensor integration and display output.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🧰Components Required
    Arduino Uno (or compatible board)
    Ultrasonic Sensor (HC-SR04)
    I2C LCD Display (16x2)
    Jumper wires
    Breadboard (optional)


🔌Wiring Instructions
    Ultrasonic Sensor:
       VCC → 5V
       GND → GND
       Trig → Pin 3
       Echo → Pin 4
    I2C LCD:
       VCC → 5V
       GND → GND
       SDA → A4
       SCL → A5


📦Library Dependencies
Make sure to install the following libraries via Arduino Library Manager:
 * LiquidCrystal_I2C by Frank de Brabander or Marco Schwartz
 * Wire (usually pre-installed)


🧪 How It Works
   * The ultrasonic sensor sends a pulse via the Trig pin.
   * The Echo pin receives the reflected pulse.
   * The time difference is used to calculate distance.
   * The result is displayed on both the LCD and Serial Monitor.
