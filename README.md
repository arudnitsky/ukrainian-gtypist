# TODO:
- Create a repo for this in github
- Add copyleft to the top of the typ files and a link to my github repo

# Ukrainian lesson file creation for GNU Typist via Claude.ai

I used Claude 3.5 Sonnet to create a Ukrainian lesson file for GNU Typist so I could practice typing in Ukrainian on my Macbook. 

Note that GNU Typist uses latin keys to navigate menus. I had to switch my keyboard to English to navigate, and switch to Ukrainian to practice typing.

## Installing GNU Typist on Mac

- Brew: Install via `brew install gnu-typist`. Formula summary page [here](https://formulae.brew.sh/formula/gnu-typist)
- MacPorts: Install via `sudo port install gtypist`. Port summary page [here](https://ports.macports.org/port/gtypist/summary)

## GNU Typist Links

- [GNU Typist Home Page](http://www.gnu.org/software/gtypist/)
- [GNU Typist Manual](https://www.gnu.org/savannah-checkouts/gnu/gtypist/gtypist.html)

## How To create your own .typ file

1. Go to <https://claude.ai/>
1. Upload the `gtypist-script-reference.txt` file to Claude 3.5 Sonnet.
1. Use the prompt in the `Claude3.5Sonnet-gtypist-prompt.txt` file to create a GNU Typist file. 
1. Copy and save the output into a `uk.typ` text file.
1. Run via `gtypist uk.typ`

## Mac Ukrainian keyboard setup

First, I installed the Ukrainian Language and Ukrainian input source in Settings. Bonus: this also allows you to dictate and translate Ukrainian via Siri. 

## Ukrainian keyboard stickers

I bought blue transparent Ukrainian keyboard overlay stickers from [Keyboard Overlay](https://keyoverlay.com/language-stickers/ukrainian/all-cyrillic-scripts-in-one-small-round-keyboard-stickers). The on-screen keyboard worked well for reference. I cleaned the keys with an alcohol wipe, and then used an Exacto knife blade to carefully peel and place the stickers on the upper right of each key. 

It will take a while. Take breaks. Don't use your fingers! Two years later the sticker are still looking good. 

## Generating more complex Ukrainian lesson text

The prompt in `prompt-in-the-style-of.txt` will generate text for more practice typing. I used Claude again, resulting in the the text found in `text-in-the-style-of.txt`. 

