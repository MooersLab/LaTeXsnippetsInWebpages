# LaTeX snippets for textareas in webpages

Sapling is a grammar checker like language-tool and Grammarly.
It is being developed at Stanford.
It works as an add-in on MS Word and an extension for Google Chrome and Firefox \footnote{\url{https://saplingai.zendesk.com/hc/en-us/articles/360041603813-Installing-Sapling}}.
Sapling can work in Overleaf and 750words, but you may have to turn it on via the Google Extension manager that is shaped like a puzzle piece.

I miss the ability to use snippets in 750words and Overleaf.
The problem is now solved via snippets in Sapling.
You can have up to 20 snippets in the free version.
Twenty snippets for LaTeX cover my most frequent needs.

The snippets have shortcuts rather than tab-triggers.
Just type the name of the shortcut, and the code is inserted.
There is no need to enter tab.

However, a shortcut like "ch" for a chapter template is too frequent of a letter seqeunce.
This leads to unwanted insertions of snippets.
The work around is to rename the above snippet "zch".
The zch letter sequence is not frequent.

Entering a blackslash will bring up a menu that provides access to your list of snippets.
Backslashes are used a lot in LaTeX so I recommend changing the short to something else like a forward slash, which is rarely used in LaTeX.

<p align="center"><img src="images/snippetsEditor.png"></p>

The snippets can be interactively entered in a menu in Google Chrome like the one shown above.
You have to use shift-enter to insert a new line character in multi-line snippets.

The collection of snippets can be downloaded in a CSV file.
It may be faster edit the CSV file with a proper text editor to add new multiline snippets and then upload the CSV file via the Sapling menu in Chrome.
I have attached my current collection of snippets in a CV file which you can upload into your Sapling account.

After a change is made to the table of snippets in your Sapling account, you have to reload the document to be able to have access to the new snippets in the text area of the webpage that you are writing in.

I am having trouble with the double insertion of multi-line snippets on Overleaf.
Single line snippets are inserted only once. I have notified Sapling and Overleaf.

The snippets support dates of any format. 
For example, {{ date %Y-%m-%d }} returns the current date in Year-Month-Day format.