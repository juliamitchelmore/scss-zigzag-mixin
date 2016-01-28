# scss-zigzag-mixin
Mixin to create a zigzag with a transparent background, using CSS linear gradients

## Usage
To implement the zigzag mixin, download the `zigzag-mixin.scss` file and include it in your project.

Creating a zigzag is then achieved via the following SCSS:

    .element
    {
        @include zigzag($colour, $height);
    }

where `$color` is the colour you want the zigzag to be, and `$height` is the height of the zigzag.

## Example

This mixin will create zigzags of any size with minimal mis-alignment.

See `zigzags.html` within the **Example** folder for a variety of zigzags at different sizes.