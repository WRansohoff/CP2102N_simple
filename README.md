# CP2102N USB \<-\> UART Board

This is a simple reference implementation of a board using the `CP2102N` USB / Serial bridge. It has a micro-USB connector on one side, and TX / RX / 3.3V / Ground pins on the other.

The other USART signals provided by the `CP2102N` are also broken out on two rows of headers along the side of the board. I haven't tested them because I don't usually use those signals, but it seemed like a good idea to make them available.

# Current Status

This is the second revision of a design that I've had some success with. I've only tested the TX / RX signals, but those seem to work fine.

I'm still waiting to receive boards with this actual design, though, so you should still think of this board as untested for now.
