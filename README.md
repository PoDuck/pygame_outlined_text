# pygame_outline_text
This is a small bit of code to easily create outlined text in pygame.

## usage
`text = OutlinedText(text, position, outline_width, font_size, screen, foreground_color=(255, 255, 255), background_color=(0, 0, 0))`

## parameters:
* **text**: bytes or unicode text
* **position**: tuple of screen position of form (x, y) where you wish text to be rendered.
* **outline_width**: outline width in pixels
* **font_size**: font size
* **screen**: pygame screen you want text rendered to
* **foreground_color**: foreground color of text defaults to white
* **background_color**: background color of text defaults to black

## methods:
`get_width()`
Returns width of text, including border.

`change_position(position)`
Changes position to coordinates in the position tuple (x, y)

`change_text(text)`
Changes the text to `text`, which is given in bytes or unicode.

`change_foreground_color(color)`
Changes the foreground color of the text.

`change_background_color(color)`
Changes the outline color of the text.

`draw()`
Blits the text to the screen.
