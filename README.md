## Grain Counting using preprocessing by Eicken and Watershed algorithm

Using old techniques given by Eicken, 1993. Using edge detection algorithms to describe textural features in Ice Thin Sections (yes, Ice is anisotropic :o it's hexagonal, and actually counts as a mineral) and using a watershed algorithm I take a Troctolite (from the Macquaire University Database) for implementing this paper and a final watershed algorithm for grain counting; the results although not perfect are quite reasonable for an old algorithm (in a few days I will try with a more recent one, HED; check my repo: https://github.com/ieferreira/Grain-Counting-HED-Algorithm).

### Binarization is left to the user, but a 20-60 lower threshold is advised


![](gif_binary.gif = 300x300)
Playing with the lower threshold for the final binarization

## Final result

The original image and the watershed one with the number of grains found

![](final.jpg)


