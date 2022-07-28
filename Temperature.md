# Temperature

## First go to ``||basic.show icon||`` and drag the heart block to the forever loop.
```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
})
```

## Next, 1. Go to ``||basic.showNumber||`` and drag shownumber to the forever loop.  2. Go to input and drag the ``||input.temperature||`` and place it ontop of the 0. 
```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showNumber(input.temperature())
})
```

## Finally, go to ``||basic.showLeds||``and drag the show string Hello to the forever loop.  
```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showNumber(input.temperature())
    basic.showString("Hello!")
})
```