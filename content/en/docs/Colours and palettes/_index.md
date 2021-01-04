
---
title: "Colours and Palettes"
linkTitle: "Colours and Palettes"
weight: 4
date: 2017-01-05
simple-list: true
description: >
  A total of sixteen colours in four complementary sub-palettes (Greys, Pinks, Purples and Colourful), together with optional ANSI terminal palette.
---
![](undraw_palette.svg)

The Rosely colour palette consists of 16 colours arranged in four groups that can be used as a basis for a user interface design or application theme. The colours blend well with each other and are intended for a low contrast calming design that emphasises serenity and beauty. There is enough contrast in the Colourful group for emphasising different text elements or parts of the application.

All colours are numbered from `rosely0` to `roselyF` (using the hexadecimal numbering scheme) where each palette has 4 colours. There is an optional 16 colour palette intended to be use in applications that rely on ANSI terminal colours.

This section provides an overview of the four sub-palettes and the 16 colours. Each colour is displayed with it's Rosely code, [PANTONE](https://www.pantone.com/color-finder) colour name and code, and RGB hex code.

## Greys

{{< swatch-group name="Greys" >}}
{{< swatch color="#27272a" code="rosely0" name="Black Beauty" pantone="19-3911 TCX" >}}
{{< swatch color="#615f5f" code="rosely1" name="Granite Gray" pantone="18-5204 TCX" >}}
{{< swatch color="#a49e9e" code="rosely2" name="Opal Gray" pantone="16-3801 TCX" >}}
{{< swatch color="#f4eee8" code="rosely3" name="Sugar Swizzle" pantone="11-0607 TCX" >}}
{{< /swatch-group >}}

These span the greyscale from black to white with two intermediate shades of grey, and are used where the design requires neutral colours, as well as for text (in light or dark modes). If a greater variation of greys are required, then it is possible to lighten or darken these shades to achieve intermediate greys.

## Pinks

{{< swatch-group name="Pinks" >}}
{{< swatch color="#ec809e" code="rosely4" name="Morning Glory" pantone="15-1920 TCX" >}}
{{< swatch color="#f7caca" code="rosely5" name="Rose Quartz" pantone="13-1520 TCX" >}}
{{< swatch color="#F8D7DD" code="rosely6" name="Barely Pink" pantone="12-2906 TCX" >}}
{{< swatch color="#f4dede" code="rosely7" name="Heavenly Pink" pantone="12-1305 TCX" >}}
{{< /swatch-group >}}

This is a group of light pinks that can be used for highlighting and backgrounds, or text with a dark background. Pink is a colour tempering passion with purity. It is the lighter, most gentle, blissful and acquiescent of the red family, and elicits an aura of innocent romance.

The base colour in this group is `rosely5` or *Rose Quartz*, a warm and embracing gentle rose tone that conveys compassion and a sense of composure.

## Purples

{{< swatch-group name="Forest Meadow" >}}
{{< swatch color="#85677b" code="rosely8" name="Grapeade" pantone="18-3211 TCX" >}}
{{< swatch color="#b565a7" code="rosely9" name="Radiant Orchid" pantone="18-3224 TCX" >}}
{{< swatch color="#be9cc1" code="roselyA" name="Lupine" pantone="16-3521 TCX" >}}
{{< swatch color="#D2C4D6" code="roselyB" name="Lavender Fog" pantone="13-3820 TCX" >}}
{{< /swatch-group >}}


These are range of dark to light purple/lilac colours that can be used for accents, borders and alternate backgrounds to complement the pinks.

The base colour in this group is `rosely9` or *Radiant Orchid*, a captivating harmony of fuchsia, purple and pink undertones, that emanates great joy, love and health.


## Colourful

{{< swatch-group name="Colourful" >}}
{{< swatch color="#d2386c" code="roselyC" name="Raspberry Sorbet" pantone="18-2043 TCX" >}}
{{< swatch color="#64bfa4" code="roselyD" name="Spearmint" pantone="15-5819 TCX" >}}
{{< swatch color="#3CADD4" code="roselyE" name="Aquarius" pantone="16-4530 TCX" >}}
{{< swatch color="#eada4f" code="roselyF" name="Meadowlark" pantone="13-0646 TCX" >}}
{{< /swatch-group >}}

These are four bright and positive colours that can be used for highlighting and brighten the design, and roughly correspond to red, green, blue and yellow.

The colours in this group include a delectable raspberry, a periwinkle blue, a cool spearmint and a vibrant sunny yellow.

## ANSI

This is an optional palette to be used in designs which require an expanded gamut and are intended to be drop in replacements for ANSI terminal colour schemes.

> The [ANSI escape code standard](https://en.wikipedia.org/wiki/ANSI_escape_code), formally adopted as [ISO/IEC 6429](https://www.ecma-international.org/publications/standards/Ecma-048.htm), defines a series of control sequences. Each control sequence begins with a *Control Sequence Inducer* (CSI), defined as an escape character followed immediately by a bracket: `ESC[`. In particular, a CSI followed by a certain number of “parameter bytes” (ASCII `0–9:;<=>?`) then the letter m forms a control sequence known as a *Select Graphic Rendition* (SGR). If no parameter bytes are explicitly given, then it is assumed to be 0. SGR parameters can be chained together with a semicolon ; as the delimiter.
>- [Information from Chris Yeh's blog post on Terminal Colours](https://chrisyeh96.github.io/2020/03/28/terminal-colors.html)

The 8 actual colors within the ranges (30-37, 40-47, 90-97, 100-107) are defined by the ANSI standard as follows:

| Last Digit | Color |
| --- | --- |
| 0 | black |
| 1 | red |
| 2 | green |
| 3 | yellow |
| 4 | blue |
| 5 | magenta |
| 6 | cyan |
| 7 | white |

The role of terminal color schemes is to map the 8 foreground colors (30-37) to RGB values. The Rosely ANSI palette supports an additional 8 colors corresponding to the bold or bright variants of the original colors (90-97).

{{< swatch-group name="ANSI Foreground" >}}
{{< swatch color="#27272a" code="black" name="Black Beauty" pantone="19-3911 TCX" >}}
{{< swatch color="#DD4124" code="red" name="Tangerine Tango" pantone="17-1463 TCX" >}}
{{< swatch color="#009473" code="green" name="Emerald" pantone="17-5641 TCX" >}}
{{< swatch color="#DFC160" code="yellow" name="Cream Gold" pantone="13-0739 TCX" >}}
{{< swatch color="#0F4C81" code="blue" name="Classic Blue" pantone="9-4052 TCX" >}}
{{< swatch color="#5F4B8B" code="magenta" name="Ultra Violet" pantone="18-3838 TCX" >}}
{{< swatch color="#45B5AA" code="cyan" name="Turquoise" pantone="15-5519 TCX" >}}
{{< swatch color="#A49E9E" code="white" name="Opal Gray" pantone="16-3801 TCX" >}}
{{< /swatch-group >}}

---

{{< swatch-group name="ANSI Bright/Bold" >}}
{{< swatch color="#615f5f" code="bright black" name="Granite Gray" pantone="18-5204 TCX" >}}
{{< swatch color="#D94F70" code="bright red" name="Honeysuckle" pantone="18-2120 TCX" >}}
{{< swatch color="#88B04B" code="bright green" name="Greenery" pantone="15-0343 TCX" >}}
{{< swatch color="#F5DF4D" code="bright yellow" name="Illuminating" pantone="13-0647 TCX" >}}
{{< swatch color="#93A9D1" code="bright blue" name="Serenity" pantone="15-3919 TCX" >}}
{{< swatch color="#CA4286" code="bright magenta" name="Fuchsia Fedora" pantone="18-2330 TCX" >}}
{{< swatch color="#C3DDD6" code="bright cyan" name="Opal Blue" pantone="12-5406 TCX" >}}
{{< swatch color="#F4EEE8" code="bright white" name="Sugar Swizzle" pantone="11-0607 TCX" >}}
{{< /swatch-group >}}
