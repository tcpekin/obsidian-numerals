# Numerals Obsidian Plugin

Numerals gives you the power of an advanced calculator inside a `math` code block, complete with currencies, units, variables, and math functions! Now you can perform calculations inline with your notes, and see both the input and the evaluated result. Numerals works with Live Preview as well as Reader view. Math expressions can be commented with `#`, or descriptive sentences can be added between calculations.
<img width="1032" alt="Numerals Lemonade Stand -Side By Side - 11-6" src="https://user-images.githubusercontent.com/1195174/200186757-a71b5e7a-df96-4350-b6a4-366d758e696d.png">

## Features
- Units
 	- `1ft + 12in` → `2ft`
	- `20 mi / 4 hr to m/s` → `2.235 m / s`
	- `9.81 m/s^2 * 100 kg * 40 m` → `39.24 kJ`
- Currency
	- `$1,000 * 2` → `2,000 USD`
	- `$10 + $0.75` → `10.75 USD`
- Math functions
	- `sin`, `cos`, `abs`, `log`, etc (see [mathjs](https://mathjs.org/docs/reference/functions.html) for full list)
- Hex, Binary, Octal, and other bases
	- `0xff + 0b100` → `259`
	- `hex(0xff + 0b100)` → `"0x103"`
- Natural Constants
	- `e`, `i`, `pi`, `speedOfLight`, `gravitationConstant`, `vacuumImpedance`, `avogadro`
	- And many more (see [mathjs: Constants](https://mathjs.org/docs/reference/constants.html) and [mathjs: Units](https://mathjs.org/docs/datatypes/units.html) for more)
	
*Numerals* utilizes the [mathjs](https://mathjs.org/) library for all calculations. *Numerals* implements a preprocessor to allow more human-friendly syntax, such as currency symbols and thousands separators. For all available functions and capabilities (which includes matrices, vectors, symbolic algebra and calculus, etc), see the [mathjs documentation](https://mathjs.org/docs/index.html)


## Style Options
Numerals has been tested with the default theme and most other top themes. It uses default values such that it should play nice with any other theme. There are 3 options to choose from:

### Layout
#### 2-panes
- Answer is shown to the right of the input with a background color and a seperator.
- Distinctive style that seperates input from evaluated answers

<img width="622" alt="Numerals 2 Panes - 11-6" src="https://user-images.githubusercontent.com/1195174/200186692-0b6a0a7b-3f77-47f8-887f-d7d333b53967.png">

#### Answer to the Right
- Answer to the right: answer is shown in the same line as the input, but right-aligned
- More subtle than 2-panes that works well with just a few calculations

<img width="622" alt="Numerals answer right - 11-6" src="https://user-images.githubusercontent.com/1195174/200186885-dedf1ccb-0464-4732-976e-0eaf54f5d098.png">

#### Answer Below
- Answer is shown below the input, on the next line. 
- Less compact vertically, but more compact horizontally

<img width="622" alt="Numerals answer below - 11-6" src="https://user-images.githubusercontent.com/1195174/200186929-8e5bf0de-ab1e-47d0-a3f3-cf5164136c62.png">

### Alternating Row Colors
Choose between a consistent code block background color (left), or alternating rows to help track from input to result (right).

<img width="1010" alt="Numerals Alternating Row Style Comparison" src="https://user-images.githubusercontent.com/1195174/200187338-24912a83-eb1e-4188-a843-e189f33e7133.png">

## Remaining features in progress
- Support for additional currency symbols (currently only supports `$`)
- Support for mapping currency symbols to different currencies (currently `$` maps to `USD`)
- Better Error handling (currently no indication of error line)
- Style Settings support for all colors and other style options
- Syntax highlighting of input
