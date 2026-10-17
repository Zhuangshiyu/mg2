# minigame 2
## Devlog
1.One issue I encountered was when I tried to assign 1.0f to an int variable called health. I realized that 1.0f is a float value, but health was declared as an integer. I fixed the error by changing 1.0f to 1, since an integer does not need a decimal point.

2.I think the period . is used to access something that belongs to an object. For example, spriteRenderer.color means accessing the color property of _spriteRenderer.
I think new is used to create a new object. In this case, new Color(r, 0.2f, 0.2f) creates a new color using the given RGB values and assigns it to the SpriteRenderer.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
