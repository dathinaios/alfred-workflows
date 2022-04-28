## SCDoc

This workflow allows for searching of the SuperCollider help files from Alfred, with autosuggestion feedback.

In order to render the help files you need to run `SCDoc.renderAll` in SuperCollider. 

Invoke Alfred and input `sd`, hit `Enter` and write the name of the helpfile you are looking for. Alternatively assign a hotkey (current selection is passed in).

![](https://raw.github.com/dathinaios/alfred-workflows/master/GitHubResources/scdocs.png)

[Click here and then `View Raw` to download](SCDoc/SCDoc.alfredworkflow)

-----------------------------------------------------
**TIPS:**

1. The search is case sensitive.
2. In the Run Script you can choose a specific editor by changing `open "{query}"` to, for example, `open -a Safari.app "{query}"`.


-----------------------------------------------------

As a starting point I used this Maven workflow by Torkild U. Resheim:

http://torkild.resheim.no/2013/04/using-alfred-2-to-run-maven-scripts.html

## Nord and Gruvbox Themes

Just download and double click the relevant file.
