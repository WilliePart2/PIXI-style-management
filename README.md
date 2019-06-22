# PIXI-style-management
Way to manage styles for PIXI.JS objects

## Main concept
Main idea is to manage PIXI.JS properties as "state" and use for this purpose reusable functions and "reducers"(for managing batch of different styles for one PIXI.JS object
* function always clear and work only with PIXI object(s) and perhapse additional params
* function always comprehensively determine which styles shold be applied to component
* we can composite diferrent functions within "final function" which will apply styles
* we can't apply styles to component from diferent "final functions"

## Description
For now i have only a demo and soon I want to create styleguide or library for managing styles in pixi.
There are many cutting-age cases which need to handle. For example applying one or twoo style to existing style state.

## Work
For now I have only this demo: [link](https://www.pixiplayground.com/#/edit/~Ob1NxqG4zrzdCXVlNsBN)
