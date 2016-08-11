# Scss Mixin for Dynamic Sprites

##Usage:

params: dynamic-sprite(width , Nr. of images, height of srite.png, path to sprite.png, direction to float)

Eg.:

@include dynamic-sprite(50px, 10, 67, 'path to sprite.png', 'left'); 

##Importan:

The param for the height of the sprite.png image is in px but dosen't go withe the actual px statement, Just the number value.

## Example

## Original Sprite:

![dynamic sprite](https://github.com/SpecialKcl/Dynamic-Sprite/blob/master/images/sprite_flags.png)


## With Mixing

Floating left:

@include dynamic-sprite(50px, 10, 67, '../images/sprite_flags.png', 'left');

![dynamic sprite](https://github.com/SpecialKcl/Dynamic-Sprite/blob/master/images/left.png)


Floating right:

@include dynamic-sprite(30px, 10, 67, '../images/sprite_flags.png', 'right'); 

![dynamic sprite](https://github.com/SpecialKcl/Dynamic-Sprite/blob/master/images/right.png)


Floating none:

@include dynamic-sprite(50px, 10, 67, '../images/sprite_flags.png', 'none'); 

![dynamic sprite](https://github.com/SpecialKcl/Dynamic-Sprite/blob/master/images/none.png)
