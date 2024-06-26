# Ukrainian lesson file creation for GNU Typist via Claude.ai

I used Claude 3.5 Sonnet to create a Ukrainian lesson file for GNU Typist so I could practice typing in Ukrainian on my Macbook. 

Note that GNU Typist uses latin keys to navigate menus. I had to switch my keyboard to English to navigate, and switch to Ukrainian to practice typing.

## Installing GNU Typist on Mac

- Brew: Install via `brew install gnu-typist`. Formula summary page [here](https://formulae.brew.sh/formula/gnu-typist)
- MacPorts: Install via `sudo port install gtypist`. Port summary page [here](https://ports.macports.org/port/gtypist/summary)

## GNU Typist Links

- [GNU Typist Home Page](http://www.gnu.org/software/gtypist/)
- [GNU Typist Manual](https://www.gnu.org/savannah-checkouts/gnu/gtypist/gtypist.html)

## Creating your own .typ file

1. Go to <https://claude.ai/>
1. Upload the `gtypist-script-reference.txt` file to Claude 3.5 Sonnet.
1. Use the prompt in the `Claude3.5Sonnet-gtypist-prompt.txt` file to create a GNU Typist file. 
1. Copy and save the output into a `uk.typ` text file.
1. Run via `gtypist uk.typ`

## Set up a Mac Ukrainian keyboard

Install the Ukrainian Language and Ukrainian input source in Settings. 

Bonus: this also allows you to dictate and translate Ukrainian via Siri. 

## Ukrainian keyboard stickers

I bought blue transparent Ukrainian keyboard overlay stickers from [Keyboard Overlay](https://keyoverlay.com/language-stickers/ukrainian/all-cyrillic-scripts-in-one-small-round-keyboard-stickers). The on-screen keyboard worked well for reference. I cleaned the keys with an alcohol wipe, and then used an Exacto knife blade to carefully peel and place the stickers on the upper right of each key. Two years later the sticker are still looking good. 

It will take a while. Take breaks. Don't use your fingers to peel the stickers off! 

## Generating more complex Ukrainian lesson text

The prompt in `prompt-in-the-style-of.txt` will generate text in the style of famous Ukrainian authors for more practice typing. I used Claude again, resulting in the the text found in `text-in-the-style-of.txt`. 

``` text
У стилі Тараса Шевченка (1814-1861), поет:

Гей, брати мої, козаки!
Чуєте, як дзвенять шаблюки?
Україна-мати кличе нас,
Щоб боронити волю в цей час.
Хай ворог лютий згине, мов жук,
Під натиском наших міцних рук!


У стилі Лесі Українки (1871-1913), поетеса і драматург:

Фея лісова, прекрасна й чарівна,
Грає на сопілці пісню дивну.
Зачаровує всіх звуком неземним,
Щоб забули про біль і жах страшний.
Хай квітне надія в серцях людей,
І зникнуть хмари над землею цією!


У стилі Михайла Грушевського (1866-1934), історик і політичний діяч:

Історія України - це літопис боротьби за волю і незалежність. Кожне покоління додає свою сторінку до цієї великої книги. Ми маємо пам'ятати уроки минулого, щоб будувати краще майбутнє. Єдність народу, його культура і мова - ось ключі до державності й процвітання нашої землі.


У стилі Ольги Кобилянської (1863-1942) Письменниця

Ґрунт під ногами тремтить, але дух мій незламний. Жіноча доля – це вічна боротьба за право бути собою. Єдине, що маю, – це слово, і ним я буду творити новий світ. Щастя не в шлюбі чи багатстві, а в свободі духу і можливості бути собою. Хай кожна жінка знайде свій шлях до самореалізації!


У стилі Миколи Куліша (1892-1937) Драматург

МИНА МАЗАЙЛО: Я хочу змінити своє прізвище! Хіба ж це культурно – Мазайло?

МОКІЙ: Батьку, схаменіться! Наше прізвище – наша історія!

УЛЯ: А я згодна з дядьком. Треба йти в ногу з часом.

РИНА: Тьху на вас! Яка ганьба!

МИНА: Єдине, чого я хочу, – це поваги!

МОКІЙ: Щастя не в прізвищі, а в любові до свого коріння!
```