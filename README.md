# k3-boot-samples
Quick Images to test openOCD processor connectivity.

# Steps

- select which ever SoC image of choice
- copy the file to sdcard as tiboot3.bin OR download over usart (if using uart boot)
- wait for test log to complete
- connect via jtag

# Images

- tiboot3-j721e-gp-sr1.0.bin based on 2020.07 SYSFW (RC1), boots to run a test case that basically startups all processors and sticks them in a loop
