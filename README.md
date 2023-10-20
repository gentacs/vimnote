# vim notes
## Modes

Description | keys | mode |
--|--|--
Change to visual mode | v | NORMAL
Change to linear visual mode | V | NORMAL
Change to normal mode | Esc | INSERT
Change to insert mode before cursor | i | NORMAL
Change to insert mode after cursor | a | NORMAL

## Motion keys

Description | keys | mode |
--|--|--
move left | h | NORMAL
move down | j | NORMAL
move up | k | NORMAL
move right | l | NORMAL
move through the words | w | NORMAL
move through the words in reverse | ge | NORMAL
move through the words in reverse. Go to the beginning of the current word | b | NORMAL
move through the words. Go to the end of the current word | e | NORMAL
Go to specific line | **line_number**G | NORMAL
Go to specific line | :**line_number** | COMMAND
Go to the top of the screen | shift + H | NORMAL
Go to the middle of the screen | shift + M | NORMAL
Go to the bottom of the screen | shift + L | NORMAL
Go to the next sentence | ) | NORMAL
Go to the previous sentence | ( | NORMAL
Go to the next paragraph | } | NORMAL
Go to the previous paragraph | { | NORMAL
Go to the next page | ctrl + f | NORMAL
Go to the previous page | ctrl + b | NORMAL
Move forward half a page | ctrl + d | NORMAL
Move backward half a page | ctrl + u | NORMAL
Move forward one line | ctrl + e | NORMAL
Move backward one line | ctrl + y | NORMAL

## Window motion

Description | keys | mode |
--|--|--
To rotate windows up/left | (ctrl + w) + R | NORMAL
To rotate windows down/right | (ctrl + w) + r | NORMAL
Move the current window to the far right | (Ctrl + w) + L | NORMAL
Move the current window to the far left | (Ctrl + w) + H | NORMAL
Move the current window to the very bottom | (Ctrl + w) + J | NORMAL
Move the current window to the very top | (Ctrl + w) + K | NORMAL

## Delete

Description | keys | mode |
--|--|--
delete/cut current line | dd | NORMAL
delete/cut current word | dw | NORMAL
delete/cut current character | x | NORMAL
delete/cut current character and change to insert mode | s | NORMAL

## Copy/Paste

Description | keys | mode |
--|--|--
Copy current line | yy | NORMAL
Copy from cursor to end of word | yw | NORMAL
Paste after cursor | p | NORMAL
Paste before cursor | P | NORMAL
Copy in register **number** (1 to 9) | "**number**y | NORMAL - VISUAL
Copy current selection | y | VISUAL

## Search/replace

Description | keys | mode |
--|--|--
Search | /string_to_find | NORMAL
Replace in current file | :%s/string_to_replace/new_string/g | COMMAND
Replace in selected block | :'<,'>s/string_to_replace/new_string/g | VISUAL
Remove highlight searchr | :noh | COMMAND

## Upper/Lower case

Description | keys | mode |
--|--|--
to lower case | u | VISUAL
to upper case | U | VISUAL
invert case | ~ | NORMAL
invert case by motion | g~**motion** | NORMAL

## Buffer

Description | keys | mode |
--|--|--
Open file | :open **file** | COMMAND
open buffers list | :buffers | COMMAND
delete open buffer | :bdelete **number** | COMMAND
create mark | m**alphabetic_letter** | NORMAL
go to mark | '**alphabetic_letter** | NORMAL
go to last edited line | '. | NORMAL
go to previous mark | '' | NORMAL

Comentarie|Comando
-------------|-------------
Set paste mode | **:set paste**
Undo | **u**
Redo | **ctrl+r**
Open file | **:open &lt;filename>**
Intercambiar archivos| **:b &lt;filename&gt;**

14 sep 13:00 916219629
