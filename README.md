
<!-- README.md is generated from README.Rmd. Please edit that file -->

# darkR

<!-- badges: start -->
<!-- badges: end -->

darkR is an RStudio theme file designed to emulate the GitHub Dark
default theme. This project was created for personal use, inspired by my
preference for the GitHub dark color scheme. It consists solely of an
`rstheme` file.

**Disclaimer:** I have little experience in CSS so the code may contain
some redundancies due to messy edits. The `rstheme` file is based on an
edited version of Ben Harrap’s, available
[here](https://github.com/benharrap/rsthemes.git).

Ben Harrap also provides a useful tutorial on creating and modifying
`rstheme` files if you want to develop your own theme.

## Installation

You can install the development version of darkR using Git:

``` r
# clone the repo
cd /your/personal/directory
git clone https://github.com/AmandaKwok28/darkR.git
```

Another (probably easier option) : You can also download the file
directly and save it in your directory

## Usage

To use the rstheme, open Rstudio and hit
`tools > Global Options > Appearance` then in the drop-down list of
editor themes, the Add… button and navigate to the rsthemes file you
just downloaded. Finally, hit apply.

## How to Modify

To modify this rstheme file, open the rstheme file in Rstudio. Rstudio
has 4 boxes that open up. In the top left box (the editor), navigate to
it’s bottom right corner and there should be a menu that allows you to
change the language of your file. Make sure to set that to CSS so that R
knows how to read it. This allows gives you a preview of all the
hexadecimal colors in the file so you don’t need to apply the theme
everytime to check your colors.

To actually apply the theme, navigate to editor themes (as detailed in
Usage section) and remove your theme then re-add it. Hit apply and the
changes should show.
