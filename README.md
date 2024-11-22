This code is a demostration on how to RPI pico can be used to interface with the RFM9x Lora module. The demostration requires two picos and two RFM9x modules, as well as three LEDs and pushbuttons. One pico will configure a module 
to continously try to transmit data, while the other controller will be used to set up the reciever. The data that is sent between the devices is a single byte that corresponds with the push buttons that are pressed on the transmitter controller.
Once the reciever gets the data, the LEDS will light up based on which buttons are held down on the transmitter.

Code Demo:
