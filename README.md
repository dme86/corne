# corne

![](https://i.imgur.com/0iWozxy.jpeg)

I am building a custom keyboard using open-source components, not just for its aesthetic appeal, but because it offers complete control and flexibility over key functions. This allows me to create custom layers for less frequently used keys and map functions like backspace to a thumb key, reducing unnecessary hand movements and improving ergonomics.

Keyboards like the Corne are designed for power users and will seamlessly integrate with my [Neovim](https://github.com/dme86/neovim)-based development environment.

# Components

Along with the Corne [PCB](https://en.wikipedia.org/wiki/Printed_circuit_board) , I opted for two 0xCB Helios - an rp2040 Controller with pro micro compatible pinout, 16MB (128Mbit) of flash, Dual ARM Cortex-M0 @133MHz, and 264kB SRAM:

|  |  |
|--|--|
|![enter image description here](https://i.imgur.com/6sWneIe.jpeg)  |![enter image description here](https://i.imgur.com/mMjpaNf.jpeg)  |


And Kailh Low Profile Choc Switches V1 Red Pro:

|  | 
|--|
|![enter image description here](https://i.imgur.com/1rUZWpv.jpeg)  | 


## Build

### Diodes

The first step involved soldering all 40 diodes onto the PCB. I had to proceed carefully, as the diodes are quite small and require correct orientation. Each diode has a small line on one side, which must align with the markings on the PCB, ensuring the orientation matches the directional symbol.

|  |  |
|--|--|
| ![enter image description here](https://i.imgur.com/mM9w4wf.jpeg) | ![enter image description here](https://i.imgur.com/r8TIVhg.jpeg) |

