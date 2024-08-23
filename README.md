# VIM_cheat_sheet
Commands to operate with  VIM file editor
# 📝 vi/vim Cheat Sheet

A quick reference guide for common `vi`/`vim` commands.

## Table of Contents
- [Basic Navigation](#basic-navigation)
- [Editing Text](#editing-text)
- [Copy, Paste, and Delete](#copy-paste-and-delete)
- [Search and Replace](#search-and-replace)
- [Saving and Exiting](#saving-and-exiting)
- [Visual Mode](#visual-mode)
- [Miscellaneous Commands](#miscellaneous-commands)

---

## Basic Navigation

| Description                            | Command         |
|----------------------------------------|-----------------|
| Move cursor left                       | `h`             |
| Move cursor right                      | `l`             |
| Move cursor up                         | `k`             |
| Move cursor down                       | `j`             |
| Move to beginning of the line          | `0` (zero)      |
| Move to end of the line                | `$`             |
| Move to the start of the file          | `gg`            |
| Move to the end of the file            | `G`             |
| Move forward one word                  | `w`             |
| Move backward one word                 | `b`             |
| Move to the next occurrence of 'x'     | `fx`            |
| Move to the previous occurrence of 'x' | `Fx`            |

---

## Editing Text

| Description                            | Command         |
|----------------------------------------|-----------------|
| Enter insert mode                      | `i`             |
| Enter insert mode at the end of line   | `A`             |
| Delete a character under the cursor    | `x`             |
| Delete a word                          | `dw`            |
| Delete a line                          | `dd`            |
| Change a word                          | `cw`            |
| Change a line (replace it)             | `cc`            |
| Undo last change                       | `u`             |
| Redo last undone change                | `Ctrl + r`      |
| Replace character under cursor         | `r` followed by the character |

---

## Copy, Paste, and Delete

| Description                            | Command         |
|----------------------------------------|-----------------|
| Copy (yank) a line                     | `yy`            |
| Copy (yank) a word                     | `yw`            |
| Copy (yank) the current character      | `y`             |
| Paste after the cursor                 | `p`             |
| Paste before the cursor                | `P`             |
| Delete a line                          | `dd`            |
| Delete from cursor to end of line      | `D`             |
| Delete from cursor to end of word      | `dw`            |
| Delete entire file content             | `ggdG`          |

---

## Search and Replace

| Description                            | Command                                |
|----------------------------------------|----------------------------------------|
| Search for a pattern                   | `/pattern`                             |
| Search for the next occurrence         | `n`                                    |
| Search for the previous occurrence     | `N`                                    |
| Search and replace within the file     | `:%s/old/new/g`                        |
| Search and replace in current line     | `:s/old/new/g`                         |
| Confirm each replacement               | `:%s/old/new/gc`                       |

---

## Saving and Exiting

| Description                            | Command         |
|----------------------------------------|-----------------|
| Save the file                          | `:w`            |
| Save the file and exit                 | `:wq` or `ZZ`   |
| Exit without saving                    | `:q!`           |
| Save as a new file                     | `:w filename`   |

---

## Visual Mode

| Description                            | Command         |
|----------------------------------------|-----------------|
| Enter visual mode                      | `v`             |
| Enter visual line mode                 | `V`             |
| Enter visual block mode                | `Ctrl + v`      |
| Yank (copy) selected text              | `y`             |
| Delete selected text                   | `d`             |
| Replace selected text with input       | `c`             |

---

## Miscellaneous Commands

| Description                            | Command         |
|----------------------------------------|-----------------|
| Open a new line below the cursor       | `o`             |
| Open a new line above the cursor       | `O`             |
| Repeat the last command                | `.`             |
| Indent selected lines                  | `>` in visual mode |
| Un-indent selected lines               | `<` in visual mode |
| Join the current line with the next    | `J`             |
| Set line numbers                       | `:set nu`       |
| Turn off line numbers                  | `:set nonu`     |
| Split window horizontally              | `:split`        |
| Split window vertically                | `:vsplit`       |
| Switch between windows                 | `Ctrl + w`      |

---

This `README.md` provides a comprehensive overview of common `vi`/`vim` commands, organized by function. It's a handy reference that can be extended as needed.
