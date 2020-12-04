# LED_device_driver
This is device driver for LED.
Blinks as many times as the number you entered (1-9).
This code uses code of https://github.com/ryuichiueda/robosys_device_drivers
Follow the procedure below.  
$cd myled  
$make  
$sudo insmod myled.ko  
$sudo chmod 666 /dev/myled0  
$echo NUMBER > /dev/myled0    (NUMBER is the number of blings)  
&sudo rmmod myled (Post-processing)  
