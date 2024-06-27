# PC Transporter GoDrive

A clone of the original Applied Engineering Transdrive adapter that allows
you to connect an Apple II PC Transporter to a standard DOS Drive.

At this time it has only been tested with Gotek Floppy Emulators but it
should allow you to use any DOS PC Drive of the era.

## BOM

The DigiKey part number reflect my most recent order - you can substitute as you see fit.

| Schematic Part | Part                       | Total Quantity | Manufacturer Part Number | DigiKey Part Number | Notes |
|----------------|----------------------------|----------------|--------------------------|---------------------|-------|
| U1             | 74LS138/1                  | 1              | TI SN74LS138N            | 296-1639-5-ND       |       |
| U2             | 7407N                      | 1              | TI SN7407N               | 296-1436-ND         |       |
| R1, R2, R3, R4 | 2.7K Resistor              | 4              | Stackpole RSMF2JT2K70    | RSMF2JT2K70CT-ND    | Any 2.7k commodity resistor will work, the pad is sized perfectly for the noted part but you definitely can use a smaller cheaper resistor. The large resistors where an aesthetic choice. |
| C1, C2         | 0.1uF Capacitor            | 2              | Nichicon UKL1H0R1MDDANA  | 493-15375-ND        |       |
| J1, J2         | 34 position keyed header   | Up to 2        | On Shore Tech 302-S341   | ED10528-ND          | This connector is optional, depends on how you want to connect your floppy drive to the board |

Total BOM cost for parts only at time of purchasing (June 13, 2023) was $11.81.

Unfortunately the DB-19 connector for the Apple II interface is not easily sourced, so it is not included here.

## License

![Creative Commons Attribution-ShareAlike 4.0 International License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
