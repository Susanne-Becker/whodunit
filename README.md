# Questions

## What's `stdint.h`?

De <stdint.h> is een header file en kan sets van integer types declareren met gespecificeerde breedtes, en zal corresponderende sets macro's definiëren.

## What's the point of using `uint8_t`, `uint32_t`, `int32_t`, and `uint16_t` in a program?

Om een bepaalde hoeveelheid geheugen opzij te zetten voor een int, in tegenstelling tot de normale 4 bytes.

## How many bytes is a `BYTE`, a `DWORD`, a `LONG`, and a `WORD`, respectively?

BYTE= 1 byte/8 bits, DWORD = 4 bytes/32 bits, LONG = 4 bytes/32 bits & WORD = 2 bytes/16 bits

## What (in ASCII, decimal, or hexadecimal) must the first two bytes of any BMP file be? Leading bytes used to identify file formats (with high probability) are generally called "magic numbers."

BM

## What's the difference between `bfSize` and `biSize`?

bfSize is de grootte in bytes in de bitmap, en biSize is het aantal bytes vereist door de structuur.

## What does it mean if `biHeight` is negative?

Als biHeight negatief is, is de bitmap een top-down en is de oorsprong in de linkerbovenhoek.

## What field in `BITMAPINFOHEADER` specifies the BMP's color depth (i.e., bits per pixel)?

biBitCount

## Why might `fopen` return `NULL` in lines 24 and 32 of `copy.c`?

Het bestand bestaat mogelijk niet of er kan niet in worden geschreven.

## Why is the third argument to `fread` always `1` in our code?

We lezen de bestanden één structuur tegelijk.

## What value does line 63 of `copy.c` assign to `padding` if `bi.biWidth` is `3`?

3

## What does `fseek` do?

Stelt je positie in het bestand naar voren met de offset die je opgeeft in de begin van het bestand of je huidige positie of het einde van het bestand, afhankelijk van wat jij kiest.

## What is `SEEK_CUR`?

Je huidige positie in het bestand.
