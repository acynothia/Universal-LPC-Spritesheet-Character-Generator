LPC Sprite Character Palettes
=============================================

I just collected all the palette variants I found where there's some consistency among the variations. Among the palettes that exist here are:

1. Hair Colors
2. Body Colors
3. Metals (maybe it should be "Materials" instead and also include wood?)
4. Cloth

Eye Colors can probably also be added in here, too.

With multi-colored assets, I think its more ideal to have a separate layer to be able to freely mix and match colors. This isn't necessary but it adds more flexibility.

I also have some combined variants:
1. Fur Colors (Body "Fur" Colors + "Hair" Colors, there's some crossover here so maybe these could be trimmed back)
2. Cloth + Metal Colors (so you can have both cloth and metal shoes/boots for example if you want)


The .json files are designed to be used with lpctools:
https://github.com/bluecarrot16/lpctools


If you start from a different source than the usual "base" color (I identify this as the palette used in the source directory of a certain color scheme), then the "source" in the .json file should be changed to the correct starting palette.

I don't know if there's any set standards for LPC palettes, this is just collecting all the common palettes that currently exist on the ULPC assets to make it easier to create palette variations. There may be assets not generated in all these palettes and some palettes might not even use any of these, it depends on the original source assets. If you use a custom palette you may need to include that custom palette color as an extra beyond the palettes that exist in here.