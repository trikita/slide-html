# Slide

The most simple plain text presentation maker.

This version is a standalone HTML page of 4K in size that you can edit in place
and get a working presentation. No other tools needed except for a text editor.
No programming knowledge is required, too.

Android implementation can be found [here](https://github.com/trikita/slide).

## Tutorial

1. Download `slide.html`.
   [Open this link](https://raw.githubusercontent.com/trikita/slide-html/master/slide.html)
   and press <kbd>Ctrl+S</kbd>.
2. Open the downloaded `slide.html` with a text editor.
3. Find the line `<pre id="slide">` (should be somewhere around line 36).
4. Edit the text. This is the contents of your presentation.
5. After you save the file - open it in your browser and see the results. You
	 can edit, save and refresh the browser to see how your presentation looks
	 like.

## Demo

Either open `slide.html` in your browser or [view it online](http://htmlpreview.github.io/?https://github.com/trikita/slide-html/blob/master/slide.html).

## Syntax

Slides are separated with a blank line.

The font size of each slide is scaled automatically to fit the screen. This is
suitable for [Takahashi method](https://en.wikipedia.org/wiki/Takahashi_method).

Headlines use a larger font size and start with `#` sign.

Emphasized text is written as bold and must be surrounded with asterisks, `*like this*`.

To print an actual asterist just write it twice, `** like this`.

Code blocks are written with monospace font and must start with at least two spaces.

To disable the special meaning of newlines, spaces or `#` put a dot at the
beginning of the line.

## Styling

Above the slide contents there is a small style block. You can specify the
default font, foreground and background colors for your slides. You can also
customize header, monospace and emphasized font styles.

## Printing

You can print your presentation, in this case the slides will be printed as small thumbnails
so that you could make notes on paper or use it as a story plan for your speech.

## Development

We really want to keep it minimal, but if you want to customize it or offer a
pull request you can edit files inside the `src` folder. Then you may open
`src/slide.html` to view your changes, or run `npm run build` to generate the
standalone `slide.html` version.

## License

Code is distributed under MIT license, feel free to use it. 

Made by [Trikita](http://trikita.co) - feel free to checkout our other works!
