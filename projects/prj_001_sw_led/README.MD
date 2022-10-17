# BASYS3 Switches and LEDs

    module sw_led(
        // Slide switch inputs
        input [15:0]sw,
        // Led outputs
        output [15:0]led
        );
        
        // Assign each sw to it's respective led
        assign led = sw;
    endmodule

All the 16 switches and LEDs are used in this simple example.  </br>

As you can see, the state of the switchs are assinged to the state  of the LEDs.

You also need to set the constraints file respectively.
