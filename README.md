# Sublime Text 3 LaTeX snippets
This is a collection of snippets to be used in Sublime Text 3 to assist writing LaTex documents.
Most snippets currently available are a port of the snippets that can be found in [this repository](https://github.com/honza/vim-snippets) that were adapted to function in ST3.

Feel free to use this collection and even add to it if you find that there is something missing :)

This repo is still a work in progress and there are frequent additions/changes, to stay up to date, add it to your watchlist.

I would like to thank [Honza](https://github.com/honza) for letting me do this project.
## How to install
#### Via the Sublime Text package manager:
1. Install Package Control if you haven't already ([how to](https://packagecontrol.io/installation)).
2. Bring up the control palette (usually ```ctrl+shift+p```), go to **Package Control: Install Package**, and search for SnipTeX.

#### Manually:
1. Clone this repository or download the files as .zip
2. Place the file in the Sublime Text 3 packages directory then restart Sublime:
    - On Windows: ```C:\Users\{user}\AppData\Roaming\Sublime Text 3\Packages```
    - On Linux: ```~/.config/sublime-text-3/Packages```

## Current available snippets
To use each snippet, write the corresponding "tab trigger" and press ```Tab```, the cursor will be automatically placed where it's most relevant.
If there are multiple fields in a snippet then pressing ```Tab``` again will take you to the next field. If you have another snippet with the same tab trigger, you will need to select which one you want in the menu and press *Enter*. To exit a multiple selection (multiple cursors) press ```Esc```. 

| Tab Trigger | Description                                           |
|:------------|:------------------------------------------------------|
| alert       | alert text                                            |
| alertblock  | alertblock environment                                |
| ali         | align(ed) environment                                 |
| begin       | \begin{}...\end{} block                               |
| block       | block environment                                     |
| bf          | bold face text                                        |
| \{          | \{ \}                                                 |
| cas         | cases environment                                     |
| center      | center environment                                    |
| cha         | document chapter                                      |
| cite        | \cite\[\]\{\}                                         |
| citea       | \citeauthor                                           |
| citen       | \citen                                                |
| citep       | \citep                                                |
| citet       | \citet                                                |
| citey       | \citeyear                                             |
| col2        | two-column environment                                |
| dmo         | declare math operator                                 |
| desc        | description environment                               |
| itd         | description \item                                     |
| emp         | emphasize text                                        |
| enq         | enquote                                               |
| enum        | enumerate environment                                 |
| enuma       | enumerate with arabic numbers                         |
| enumi       | enumerate with small roman characters                 |
| eqnarray    | eqnarray environment                                  |
| eq          | equation environment                                  |
| example     | exampleblock environment                              |
| fig         | figure environment (includegraphics)                  |
| figure      | reference to a figure                                 |
| fcite       | \footcite[]{}                                         |
| ft          | \footnote                                             |
| frac        | fraction                                              |
| frame       | frame environment                                     |
| gat         | gather(ed) environment                                |
| href        | \href{}{}                                             |
| index       | \index                                                |
| ita         | italic text                                           |
| it          | new list item                                         |
| item        | itemize environment                                   |
| ]i          | endless new item                                      |
| lab         | \label                                                |
| eql         | labelled equation environment                         |
| lim         | limit (math)                                          |
| listing     | reference to a listing                                |
| lr          | left right                                            |
| lra         | langle rangle                                         |
| lr{         | left\{ right\}                                        |
| lr\         | left\| right\|                                        |
| lr\(        | left\( right\)                                        |
| lr\[        | left\[ right\]                                        |
| lsi         | \lstinline                                            |
| lst         | code listing                                          |
| mc          | mathcal                                               |
| mf          | mathfrak                                              |
| ms          | mathscr                                               |
| mat         | smart matrix environment                              |
| multicol2   | two-column environment with multicol                  |
| nc          | create a new command                                  |
| nuc         | new unicode char                                      |
| ni          | \noindent                                             |
| over        | overline text                                         |
| page        | reference to a page                                   |
| par         | paragraph                                             |
| part        | document \part                                        |
| rm          | roman font text                                       |
| sf          | sans serif text                                       |
| sec         | document section                                      |
| sub         | document subsection                                   |
| ssub        | document subsubsection                                |
| section     | reference to a section                                |
| sc          | small caps text                                       |
| spl         | split environment                                     |
| stackrel    | \stackrel\{\}\{\}                                     |
| subfig      | subfigure environment                                 |
| subp        | subparagraph                                          |
| tsub        | subscripted test                                      |
| sum         | \sum^\{\}\_\{\}                                       |
| tsup        | superscripted text                                    |
| table       | reference to a table                                  |
| tab         | tabular (or arbitrary) environment                    |
| thm         | thm (or arbitrary) environment with optional argument |
| tikzcd*     | tikzcd environment in equation*                       |
| tikz        | figure environment (tikzpicture)                      |
| tikzcd      | tikzcd environment in equation                        |
| tt          | monospace text                                        |
| under       | underline text                                        |
| \           | unnumbered equation                                   |
| eq*         | unnumbered equation environment                       |
| sec*        | unnumbered section                                    |
| sub*        | unnumbered subsection                                 |
| ssub*       | unnumbered subsubsection                              |
| url         | \url\{\}                                              |
| up          | \usepackage\{\}                                       |
