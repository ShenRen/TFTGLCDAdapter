# Firmware for TFTGLCDAdapter

Firmware for TFT GLCD Adapter created with CoIDE but may be built wiht simple Makefile. Also you may use VSCode as IDE.

Read and change **inc/defines.h** to set proper parameters.

## Main parameters
* `INVERT_ENCODER_DIR`            - change direction for encoder
* `WITHOUT_HEAT_ICO`              - if you want see "FAN %" text insted heat icon on 320x240 screen
* `ILI9325`, `ILI9327`, `ILI9341` - LCD chip. Select only one of them
* `LANDSCAPE_L`                   - orientation LCD when LCD chip placed left
* `FONT`                          - font for text. Courier_New_Bold or LiberationMono
* `CHAR_WIDTH` and `CHAR_HEIGTH`  - font size
* `BUZ_FREQ_MP`                   - buzzer frequency multiplier. Change to get more suitable tones
* `LOGO_FREQ`                     - buzzer frequency for start logo