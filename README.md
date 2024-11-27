## Nord and Gruvbox Themes

Just download and double click the relevant file.

## Draft

Create a draft file for any file extension and open it. If the file has been created before it will just open the saved version.

Invoke Alfred and input `draft`, hit `Enter` to get the default `.md` file. Leave a space and wite an extension for a different file. For instance to get a Rust language file write `rs` and then press `Enter`.

[Click here and then `View Raw` to download](Draft/Draft.alfredworkflow)

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
