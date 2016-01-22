# stylep-visibility
<img src=https://avatars1.githubusercontent.com/u/16121328?v=3&s=200 title=stylep-visibility align=right height=95>

Everything you need to get started making a new style pattern.

## Install
You can install using the [spm](https://github.com/stylep/stylep) command or install using npm and the project title.

``` shell
spm install visibility
```

## Usage
``` css
/* visibility.css */

@import “stylep-visibility”;

.hidden-object {

  /* Hiding Design Pattern */
  @mixin cloak;
}

.hidden-object.active {

  /* Show the object */
  @mixin unveil;
}
```

## Patterns
Placeholder selectors that contain common styles for the box and visual state.

#### `@mixin compress;`
This scales down the element to 1px in size and places it absolute.

#### `@mixin cloak;`
Smoothly fade out your object’s visibility. Best used with unveil.

#### `@mixin unveil;`
A gradual fade in for your object’s visibility. Best used with cloak.

#### `@mixin conceal;`
Completely remove the object from the box model. Best used with reveal.

#### `@mixin reveal;`
Revert to inheritence to show your object. Best used with conceal.

#### `@mixin chop;`
Cut down your object’s size to zero, effectively hiding the object..

#### `@mixin dislocate;`
This takes your object and throws it as far off the viewport as possible.

## License
This project is licensed under the MIT [license](LICENSE).
