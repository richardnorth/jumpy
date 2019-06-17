The SparkFun MPU-9250 IMU Breakout features the latest 9-axis MEMS sensor from InvenSense. Each of these 9DoF breakouts feature an MPU-9250 with a System in Package (SiP) that combines two chips: the MPU-6500, which contains a 3-axis gyroscope as well as a 3-axis accelerometer, and the AK8963, which features a 3-axis magnetometer. This breakout has been designed to be smaller than some of our other offerings to fit in smaller projects. However, if you plan to use a breadboard, or secure the IMU board to a project with something like epoxy, the mounting holes can be easily snapped off.

To achieve its smaller size, the MPU-9250 Breakout features PTH pins that have been wrapped around the border of the PCB in three rows of three or four. The top row (J1) is all one needs to get the most functionality out of the IMU. These include the I2C and power interface. The second most likely to be used set of PTHs are found along the bottom (J3). This includes the address pin, the interrupt pin, and the IO voltage supply for easy interface with a more modern 1.8V processor. The third, a non-breadboard-compatible row (J2), is used for features like running other I2C devices as slaves to this one. For prototyping with these connections, throw your connections on top as you would with an Arduino Pro Mini or similar product.

The MPU-9250 replaces the popular EOL MPU-9150 and decreases power consumption by 44 percent. According to InvenSense, “Gyro noise performance is 3x better, and compass full-scale range is over 4x better than competitive offerings.” The MPU-9250 uses 16-bit Analog-to-Digital Converters (ADCs) for digitizing all nine axes, making it a very stable 9 Degrees of Freedom board

Features:
    Digital-output X-, Y-, and Z-axis angular rate sensors (gyroscopes) with a user-programmable full-scale range of ±250, ±500, ±1,000 and ±2,000°/sec and integrated 16-bit ADCs
    Digital-output triple-axis accelerometer with a programmable full-scale range of ±2g, ±4g, ±8g and ±16g and integrated 16-bit ADCs
    3-axis silicon monolithic Hall-effect magnetic sensor with magnetic concentrator
    Digitally programmable low-pass Gyroscope filter
    Gyroscope operating current: 3.2mA
    Accelerometer normal operating current: 450µA
    Magnetometer normal operating current: 280µA at 8Hz repetition rate
    VDD supply voltage range of 2.4 – 3.6V
    Small board design
    Detachable mounting holes

https://www.sparkfun.com/products/13762
https://learn.sparkfun.com/tutorials/mpu-9250-hookup-guide
https://github.com/sparkfun/SparkFun_MPU-9250_Breakout_Arduino_Library
https://github.com/sparkfun/MPU-9250_Breakout
