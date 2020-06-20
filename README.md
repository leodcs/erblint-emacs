# ErbLint.el

## Description

A simple Emacs interface for checking html ERB files using [Shopify's Erblint tool](https://github.com/Shopify/erb-lint).

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

Command                                         | Description                                             |
------------------------------------------------|---------------------------------------------------------|
<kbd>M-x erblint-check-project</kbd>            | Runs ErbLint on the entire project                      |
<kbd>M-x erblint-check-directory</kbd>          | Prompts from a directory on which to run ErbLint        |
<kbd>M-x erblint-autocorrect-project</kbd>      | Runs auto-correct on the entire project                 |
<kbd>M-x erblint-autocorrect-directory</kbd>    | Prompts for a directory on which to run auto-correct    |
<kbd>M-x erblint-check-current-file</kbd>       | Runs ErbLint on current file                            |
<kbd>M-x erblint-autocorrect-current-file</kbd> | Runs auto-correct on current file                       |


### MELPA

// Soon

## Bugs & Improvements

Bug reports and suggestions for improvements are always welcome and so are Pull Requests.
