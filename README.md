# minigame 2
## Devlog
Write your Devlog here.
q1: In Step 2 of the Spell script, after I uncommented the if statement, I got an error because there were no parentheses around the condition after if. In C#, the condition of an if statement has to be inside parentheses, so I fixed it by changing if _timeLeft <= 0.0 to if (_timeLeft <= 0.0). 
q2: I think this line changes the color of the chest. I think the period (.) is used to point to the color of the sprite renderer, so `_spriteRenderer.color` means the color that belongs to the sprite renderer. I think the word `new` makes a new chest.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
