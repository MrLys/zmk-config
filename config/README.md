# How to make this work.
I couldnt make it work properly without copying it into the zmk repo. Something like this did not work: `west build --pristine -d build/right -b "glove80_rh" -- -DZMK_CONFIG='<path>'`
```
cp ~/projects/zmk-config/config/glove80.keymap ~/projects/zmk/app/boards/arm/glove80/ && west build --pristine -b "glove80_lh"
```
