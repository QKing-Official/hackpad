# hackpad
My design for Blueprints HackPad and my first PCB!

I have designed my own design of the HackPad.
I have placed 6 switches, each wired to it's own GPIO pin so it's easier to work with it software-wise.
I have carefully read the pinout for the rp2040 and based my connection on the support each pin has.
This PCB is focussed on software support, since I love that part the most.
I also added an 4 pin male header to later connect the OLED display to the HackPad.
This oled display will be used for various types of data.
Since I focussed this PCB on software I also chained the RGB-LED's to each other since they would otherwise take up all other pins.
Since they should be iduvidually controllable, this is no issue.
I have properly grounded the PCB using groundplains to ensure proper functionality.
I have tried to size the PCB properly, but this might have been an issue. Its ~87.25mm x 56.24mm.
The case that I designed is small and ensures proper acces to all io.
