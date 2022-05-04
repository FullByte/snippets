# Snippets

A collection of snippets that came in handy for me.

## Snippets for vscode

To keep the snippets for vscode in sync between vscode an this repo, I use a [juction](https://docs.microsoft.com/en-us/windows/win32/fileio/hard-links-and-junctions) link to the vscode %appdata% folder e.g.:

``` ps1
New-Item -Path E:\github\snippets\vscode -ItemType Junction -Value C:\Users\0xfab1\AppData\Roaming\Code\User\snippets
```
