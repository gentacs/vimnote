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

## Buffer

Description | keys | mode |
--|--|--
Open file | :open **file** | COMMAND
open buffers list | :buffers | COMMAND
delete open buffer | :bdelete **number** | COMMAND

Comentarie|Comando
-------------|-------------
Insertar directorio| **ctrl+x ctrl+f**
Establecer modo pegar| **:set paste**
Deshacer| **u**
Rehacer| **ctrl+r**
Abrir archivos| **:open &lt;filename>**
Intercambiar archivos| **:b &lt;filename&gt;**
