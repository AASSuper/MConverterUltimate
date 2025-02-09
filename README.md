﻿# MConverterUltimate

MConverterUltimate are 6 map converters compiled into one for Minecraft. It is built upon [ljyloo's](http://github.com/ljyloo) [LevelDb2Anvil](http://github.com/ljyloo/LevelDb2Avnil) and [Anvil2LevelDb](https://github.com/ljyloo/LevelDb2Avnil/tree/Avnil2LevelDb) converter. 

## Supported World Formats

- LevelDB
- Anvil
- MCRegion
- Xbox World Format

## Converters

- Anvil to LevelDB
- Anvil to MCRegion
- LevelDB to Anvil
- MCRegion to Anvil
- Xbox to Anvil

## Warnings

The LevelDB to Anvil and Anvil to LevelDB converters will experience an error if you have blocks which are not supported by Minecraft PC Edition. It will make your .mca files corrupted, therefore please replace those blocks with another block that is supported.

## How to use most world converters(Xbox excepted)

Import your world in and rename that folder to ‘world’. Run the start.bat file(if you’re on Windows) or start.sh(if you’re on any other platform) to start the converter. The converter will now convert your world to an output folder, or the same original world folder depending on the converter you are using.

## How to use the Xbox to Anvil world converter

- Double click Converter.exe.
- Click File, then click Open.
- Navigate to your savegame.dat file and open it.
- Press "Begin conversion", then follow the instructions presented to you by the program.
- Open Minecraft and play your converted world.

## Resources

This program uses [leveldb by tinfoiled](https://github.com/ljyloo/leveldb).

This program contains [code from Mojang](https://mojang.com/2012/02/new-minecraft-map-format-anvil/)

The [LevelDB to Anvil](https://github.com/ljyloo/LevelDb2Avnil) and [Anvil to LevelDB](https://github.com/ljyloo/LevelDb2Avnil/tree/Avnil2LevelDb) converter was written by [ljyloo](https://github.com/ljyloo).

The [Anvil to MCRegion](http://www.mediafire.com/download/13g2zdwq6ram09u/Converter.zip) converter was written by Anonymous(if you are the authorised author, please contact the [Imagical Corporation](http://github.com/ImagicalCorp) to put your name down).

The [MCRegion to Anvil](https://mojang.com/2012/02/new-minecraft-map-format-anvil/) converter was written by Jens Bergensten at Mojang.

The [Xbox to Anvil](http://sourceforge.net/projects/xboxtopcminecraftconverter/) converter was writtem by [manfromscene24](http://sourceforge.net/u/manfromscene24/profile/).

## Notes

This tool was compiled and is maintained by [Keith](http://github.com/keithkfng) of the [Imagical Corporation](http://github.com/ImagicalCorp) mainly for the [Killa Server Network for MCPE](http://www.killasg.ml). This is not a tool for everyone, this is a tool for our intended use. Hopefully you find it useful too.
