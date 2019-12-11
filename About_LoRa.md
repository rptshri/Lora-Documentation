# Frequency
The RFM69HCW transmits in the `ISM (Industry Scientific and Medical) band`, a set of frequencies set aside for `low-power, short-range, license-free radios`.

SparkFun sells two versions of the RFM69HCW, a `915 MHz version` and a `434 MHz version`. These frequencies are legal in different areas: very roughly, 915 MHz is for use in the Americas and Australia, and the 434 MHz version is for use in Europe, Asia and Africa. The actual regulations are a bit of a patchwork, so `check your local regulations for other areas`.

### Note: 
>Because of the `low power` and `short range`, the limited use of either frequency isn't likely to be an issue. But if you're planning on creating a commercial product or deploying a large number of modules, be sure you're using the correct frequency for your location.

# Range
How far will the signal reach? Outside with few obstructions, you should be able to get a solid link for `hundreds of meters`. Indoors we've seen it work for over `50 meters through multiple walls`.

The RFM69HCW is capable of transmitting at up to `100 mW and up to 300 kb/s`, but you can change both of those values to fit your application. For example, you can maximize range by increasing the transmit power and reducing the data rate. Or you can reduce both for short-range wireless sensor networks that sip battery power.

# Connections
|    Arduino                | RFM95/96/97/98              |
|:-------------------------:|:----------------------------|
|                GND        |GND   (ground in)            |
|                3V3        |3.3V  (3.3V in)              |
|interrupt 0 pin D2         |DIO0  (interrupt request out)|
|         SS pin D10        |NSS   (CS chip select in)    |
|        SCK pin D13        |SCK   (SPI clock in)         |
|       MOSI pin D11        |MOSI  (SPI Data in)          |
|       MISO pin D12        |MISO  (SPI Data out)         |
|                                                         |