No gifs/vidoes, just showing the transformation that's done. If something is highlighted
in blue, that means it's highlighted inside of vscode before executing the command.

# Sort Imports

Arguments: `/['"]/`

Note: Don't expect import sorting to work if you have multi line imports.
This extension was not made to sort import, it's just able to do it in certain
cases due to the regex argument.

![sort imports](assets/previews/sort-imports-normal.png)

# Sort by Numbers

Arguments: `-n`

![sort by numbers](assets/previews/number-normal.png)

# Sort Switch Block

Arguments: none

![sort switch block](assets/previews/switch-case-normal.png)

# Sort Reverse & Remove Duplicates

Arguments: `-su`

![sort reverse & remove duplicates](assets/previews/unique-reverse.png)

# Sort HTML Elements

Note: Don't expect sorting html elements to work. Once again this extension
is not language aware (execept markdown). This is only possible due to `--section-seperator`

<!-- prettier-ignore -->
Arguments: 
```text
--section-seperator "/^    <div/"
```
![sort html children elements](assets/previews/section-seperator-html.png)
