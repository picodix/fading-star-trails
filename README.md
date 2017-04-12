## Fading star trails Photoshop script

Small Photoshop script to create a fading star trails effect out of a group of selected layers.

### Methodology

Loop through all selected layers and process like so:
- change the blend mode to `Lighten`
- change the opacity step by step all the way down from 100% to around 0%

### Todo:

- [ ] Add ability to control the direction (basically reverse the effect)
- [ ] Custom blend mode