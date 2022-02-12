
# The Climb

## Step 1 MaxZ
MaxZ Your challenge is to ``||mobs:jump||`` really high to climb up to the inaccessible area. 


```ghost
loops.forever(function () {
    mobs.applyEffect(JUMP_BOOST, mobs.target(NEAREST_PLAYER), 10, 1)
    mobs.clearEffect(mobs.target(NEAREST_PLAYER))
})
```
