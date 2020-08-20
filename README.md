# About Area Measurment Meter

**This code measure areas with straight sides using ultrasonic sensor and arduino.**

## Used Elements

- Arduino Uno
- Ultrasonic Sensor HC-SR04
- Step Motor
- Speaker
- Push Button
- Battery

## Working principle 
Place the ultrasonic sensor perpendicular to the arduino and than place the arduino on the top of the step motor. Place the whole device inside straight sided area, and press the push button. The motor will start rotating and the arduino will start calculating the measured distances from the ultrasonic sensor. When the motor will stop rotating, a voice will say the measured area.

## Testing
This code was tested using the listed elements on rectangular areas with maximum width of 2.4 meters.

The avarge time of calculating the area was about 2.4 seconds.

The measured accuracy from the true value was around 2%.

Sometimes if you place the sensor at very step angles, the device may bug itself.
