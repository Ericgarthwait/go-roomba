Go-Roomba
===
A go library for interacting with iRobot Roomba or Create robots following the Open Interface (OI) specification.

Details
---
The code of the library is remotely inspired by `pyrobot` library by damonkohler@gmail.com (Damon Kohler)

I'm still not sure on how to package go libraries, but 

    go get github.com/xa4a/go-roomba/go-roomba-test
    go-roomba-test  # -port=/dev/roomba_serial_port

Should output:

    2012/10/29 16:41:40 Failed to open serial port: /dev/cu.usbserial-FTTL3AW0
    2012/10/29 16:41:40 Making roomba failed
    exit status 1
   
And if you have Roomba connected to the specified port (`/dev/cu.usbserial-FTTL3AW0` above) it may move forward a bit.
