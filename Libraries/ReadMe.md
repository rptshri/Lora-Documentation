# Library Links (for downloading latest releases)
- [sandeepmistry/arduino-LoRa](https://github.com/sandeepmistry/arduino-LoRa) (better for getting started and learning things)

- [nootropicdesign/lora-mesh](https://github.com/nootropicdesign/lora-mesh) (If you want to implement mesh)
    

# Arduino IDE basic setups for LoRa Node

- Install latest Arduino IDE from the link provided above.

- Open Arduino IDE.

    >First Download the latest Zip from the links given above, Now we are going to include necessarry libraries to build firmware for LoRa node.

- First of all, download this ZIP file. Then in Arduino IDE, go to Sketch -> Include Library -> Add .ZIP library, select the downloaded ZIP file then open.

- You should be able to see the libraries in Sketch -> Include Library drop down list and example codes in Files -> Examples ->LoRa 

- For getting Started connect two RFM nodes to controller and flash LoRa Sender code in one node and LoRa Receiver in another node.
    >These codes can be found on path Files -> Examples ->LoRa on Arduino Ide or in examples folder in Sandeepmistry library.