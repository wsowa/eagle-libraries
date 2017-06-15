# stpm34-eagle-library

## STPM34
This is an Eagle library containing ST's STPM34 chip (ASSP for metering applications with up to four independent 24-bit 2nd order sigma-delta ADCs, 4 MHz OSF and 2 embedded PGLNA). Datasheet: http://www.st.com/content/st_com/en/products/data-converters/metering-ics/stpm34.html

## STPM33

STPM33 is the same package as STPM34. The only difference is that pins 15 & 16 are not connected in STPM33 so you can use this library for STPM33 as it is simply by not connecting these two pins.

## STPM32

STPM32 comes in smaller package (QFN24 instead of QFN32) which this library doesn't contain. If you need to use STPM32 in eagle then you will need to modify this library. If you do so, please pull request so others can use it too.
