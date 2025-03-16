# Madras bootloader & firmware

## Bootloader

usbasploader: https://github.com/hsgw/USBaspLoader/tree/plaid

fuse: `-U lfuse:w:0xd7:m -U hfuse:w:0xd0:m -U efuse:w:0x04:m`

## Firmware

- vial  
  https://github.com/hsgw/vial-qmk/tree/dm9records/madras

### To enter bootloader mode

1. Push `Reset` and hold
2. Push `Boot` and hold
3. Release `Reset`
4. If it is recognized as usbasp, Release `Boot`

### Program firmware

QMK Toolbox  
https://github.com/qmk/qmk_toolbox
