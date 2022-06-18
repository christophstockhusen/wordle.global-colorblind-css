# Local Override CSS for wordle.global for colorblind players

Enjoy playing [wordle.global](https://wordle.global)? Annoyed by making stupid guesses because you
confuse the colors?

As much as I like playing wordle on wordle.global, I often had frustrating
moments when I realized that a letter I thought was in the right position
actually wasn't. The chosen default colors are really hard to recognize for me
as a colorblind person.

Luckily, Chrome has a feature called [Local
Overrides](https://developer.chrome.com/blog/new-in-devtools-65/#overrides) that
allow you to customize the website's CSS. I used this feature to replace the default colors:

- ![#0154A6](https://via.placeholder.com/15/0154A6/000000?text=+) for letters that are contained in the word, but that are not at the right position by now.
- ![#F7951F](https://via.placeholder.com/15/F7951F/000000?text=+) for letters that are at the right position.

Thanks to [Datawrapper](https://blog.datawrapper.de/colorblindness-part2) for their series on colorblindness!

## How it looks like

### Default

<img src=hoelle_default.png>

### Adjusted

<img src=hoelle_custom.png>

## Installation

1. Clone the repository or just download the folder `css` to your local machine.
1. Open Chrome
1. Open Chromes developer tools (`Menu > More Tools > Developer Tools`) (Windows/Linux: `Ctrl+Shift+J`, Mac: `Ctrl+Option+J`)
1. Navigate to `Sources > Overrides` and select the folder `css` as override.
1. Allow Chrome to access the selected folder.
1. Done.
