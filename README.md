# ErbLint.el

## Description

An interface for checking HTML ERB files using [Shopify's Erblint tool](https://github.com/Shopify/erb-lint).

## Installation

Put `erblint.el` in your extensions folder and add this folder to your `load-path` like so:
```lisp
(add-to-list 'load-path "~/.emacs.d/<YOUR-FOLDER>")
```
and then require it:
```lisp
(require 'erblint)
```


## Usage

Command                                     | Description                                             |
--------------------------------------------|---------------------------------------------------------|
<kbd>erblint-check-current-file</kbd>       | Runs ErbLint on current file                            |
<kbd>erblint-autocorrect-current-file</kbd> | Runs auto-correct on current file                       |
<kbd>erblint-check-directory</kbd>          | Prompts from a directory on which to run ErbLint        |
<kbd>erblint-autocorrect-directory</kbd>    | Prompts for a directory on which to run auto-correct    |
<kbd>erblint-check-project</kbd>            | Runs ErbLint on the entire project                      |
<kbd>erblint-autocorrect-project</kbd>      | Runs auto-correct on the entire project                 |

## Bugs & Improvements

Bug reports and suggestions for improvements are always welcome and so are Pull Requests.
