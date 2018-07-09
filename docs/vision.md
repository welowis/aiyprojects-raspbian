# Vision Bonnet

## Pinout (40-pin header)

```
                   3.3V --> 1    2 <-- 5V
                I2C_SDA --> 3    4 <-- 5V
                I2C_SCL --> 5    6 <-- GND
                            7    8
                    GND --> 9   10
                            11  12
                            13  14 <-- GND
  (GPIO_22) BUZZER_GPIO --> 15  16 <-- BUTTON_GPIO (GPIO_23)
                   3.3V --> 17  18
               SPI_MOSI --> 19  20 <-- GND
               SPI_MISO --> 21  22
               SPI_SCLK --> 23  24 <-- SPI_CE_MRD
                    GND --> 25  26
                 ID_SDA --> 27  28 <-- ID_SCL
                            29  30 <-- GND
          PI_TO_MRD_IRQ --> 31  32
          MRD_TO_PI_IRQ --> 33  34 <-- GND
                            35  36
             MRD_UNUSED --> 37  38
                    GND --> 39  40
```