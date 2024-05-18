# LaTeX snippets for text areas in web pages via Sapling

![Version](https://img.shields.io/static/v1?label=LaTeXsnippetsInWebpages&message=0.2&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Problem addressed by this repository
I miss the ability to use snippets of LaTeX code in the text areas of 750words, Overleaf, and other websites. 
The problem is now solved via snippets in Sapling. 
You can have up to 20 snippets in the free version. 
Twenty snippets for LaTeX meet my most frequent needs.

## Alternate solution

I have not been using Sapling and this approach recently.
Instead, I use GhostText to edit text areas in a leading text editor, or I use voice-triggered snippets via Voice In Plus, Serenade, or Talon Voice.

## Solution with Sapling
Sapling is a grammar-checker like Language Tool and Grammarly. 
It is being developed at Stanford. 
Sapling is also available as an add-in on MS Word and an extension for [Google Chrome and Firefox](https://saplingai.zendesk.com/hc/en-us/articles/360041603813-Installing-Sapling). 
You may have to turn Sapling on for a specific webpage via the Google Extension Manager that is shaped like a puzzle piece.

The Sapling snippets have shortcuts rather than tab triggers. 
Type the name of the shortcut, and the code is inserted. 
There is no need to enter the tab key.

However, a shortcut like "ch" for a chapter template is too frequent of a letter sequence. 
This leads to unwanted insertions of snippets. 
The workaround is to rename the above snippet `zch'. 
The zch letter sequence is not frequent.

Entering a backslash will bring up a menu that provides access to your list of snippets. 
Backslashes are often used in LaTeX, so I recommend changing the shortcut to a forward slash, which is rarely used. 
An example of the forward-slash invoking the snippet menu is shown below.

<p align="center"><img src="images/backslash.png" style="width: 40vw; min-width: 330px;"></p>

You can access the snippet library to edit or add snippets via the menu for your Sapling account.
A table like the one below will appear after clicking on **Snippets** in the left column.
Click on the **edit** button to edit a specific snippet.

<p align="center"><img src="images/snippetsEditor.png" style="width: 85vw; min-width: 330px;"></p>


A new snippet can be interactively entered in a menu in Google Chrome like the one shown below.
You must use shift-enter to insert a new line character at the end of each line in multi-line snippets.

<p align="center"><img src="images/snippetEditorSingle.png" style="width: 55vw; min-width: 330px;"></p>

The collection of snippets can be downloaded in a CSV file. 
It may be faster to edit the CSV file with a proper text editor to add new multiline snippets and then upload the CSV file via the Sapling menu in Chrome.
I have attached my current collection of snippets in a CSV file, which you can upload to your Sapling account.

## Some caveats

After a change is made to the table of snippets in your Sapling account, you have to reload the webpage to be able to have access to the updated snippets in the text area of the webpage where you are entering text.

I am having trouble with the double insertion of multi-line snippets on Overleaf. Single-line snippets are inserted only once. I have notified Sapling and Overleaf.

The Sapling snippets support dates of any format. 
For example, {{ date %Y-%m-%d }} returns the current date in Year-Month-Day format.
See the Sapling documentation for more examples of automated parameter entry.



## Update history

|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |  Added funding and update table. Minor edits.                                                                                                            | 2024 May 18           |

## Funding
- NIH: R01 CA242845, R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel); P20GM103640 and P30GM145423 (PI: A. West)

