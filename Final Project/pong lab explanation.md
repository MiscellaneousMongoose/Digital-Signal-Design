## Why is this needed?

Pong Lab provides the code required to draw the bat and ball on the screen and also causes the ball to bounce when it when it collides with the bat or one of the walls.
The file responsible for this is bat_n_ball.vhd

The adc_if.vhd file shows how the data from the controller is prepaired to be used for controlling the bat

The pong.vhd file  makes it so that the BTN0 on the Nexys2 board may be used to initiate a serve,
generates timing signals for the VGA and ADC modules,

