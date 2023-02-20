Since the Linux Association is still reviewing the new PL2303G Linux driver, 
Please update the PL2303G Linux driver in the following way.

1. Please find the nearest Linux kernel version first.
2. make all // make a new driver.
3. sudo rmmod pl2303.ko // remove driver
4. sudo insmod pl2303.ko // add_1 a new driver
5. sudo cp pl2303.ko /lib/modules/$(uname r)/kernel/drivers/usb/serial // add_2 a new driver

If there is no version you need above, please write email to us..

Email: sales@prolific.com.tw