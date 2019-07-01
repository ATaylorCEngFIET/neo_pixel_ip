# neo_pixel_ip
IP block for driving NeoPixels from a FPGA - Device independent 

This IP block is a VHDL block inteded to drive neo pixels. It can drive up to 1023 neo pixels. 
It is designed interface with a BRAM which has atleast 24 bit data width as the pixels ad 8:8:8 RGB

The first neo pixel in the string is stored at address offset 0x4 

Address 0x0 should be the number of neopixels in the string, once this is set the pixels will be cycled through 
