### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly false
### @hideIteration true 
### @explicitHints 1

## Beams of Color

# Beams of Color
Help Wonder Women place stained glass over the beams of light to match the color sequence displayed on the wall. You'll need to tell her where to move and which colors to place. 

**Blocks Available:**  
*Place <color> Stained Glass <direction>* - Place a piece of colored stained glass in the specified direction.  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*repeat <number> times* - Repeat code the specified number of times.  

```ghost

for (let index = 0; index < 4; index++) {
    ww.placeBlock(BeamsGlass.YellowStainedGlass, Direction.Forward)
    ww.moveWW(Direction.Forward, 0)
}
player.onChat("run", function () {
	
})
```

```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```