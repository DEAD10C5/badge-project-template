# Notes

* Import the jpg/png to inkscape
  * [Outline the image](https://www.youtube.com/watch?v=lcmY77oxd8w)
  * [How to add logo or image on the PCB board silkscreen layer in KiCad v5](https://acoptex.com/wp/how-to-add-logo-or-image-on-the-pcb-board-in-kicad-v5/)

## Use KiBot to generate gerbers

[Here is a link to KiBot](https://github.com/INTI-CMNB/KiBot)

## GH Action

[Page about kicad-exports](https://github.com/marketplace/actions/kicad-exports)

Maybe install like so

```sh
cd /tmp
git clone --recursive https://github.com/nerdyscout/kicad-exports ki
cd ki && make && make install
cd /home/franklin/workspace/esp32-dev-breakout
```

Run like so:

```sh
bash kicad-exports -c docs/gerbers.kibot.yaml
```

Run a bundle like so:

```sh
bash kicad-exports -c docs/fabrication.default.kibot.lst
```

https://savjee.be/2019/12/esp32-tips-to-increase-battery-life/
https://www.lab4iot.com/2019/07/07/soldering-the-esp32-wroom-to-pcb/
https://www.youtube.com/watch?v=62WiPscjh4Y

https://www.pcbway.com/blog/PCB_Design_Tutorial/How_to_make_your_own_ESP32_breakout_board_with_minimal_circuit.html