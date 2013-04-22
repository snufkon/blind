blind.el
========

Simple transparent functions for emacs lisp

## Installation
Add the following to your emacs init file:

    (add-to-list 'load-path "/folder/containing/file")
    (require 'blind)


## Functions

`blind-up`: Transparency increases.   
`blind-down`: Transparency decreases. 


## Configuration

You can change blind up and down unit:

    (setq blind-up-and-down-unit 20)

Default value is 5 (range: `1`〜`100`).


## Key bindings

`blind-up` and `blind-down` function is not assigned to any key.

You can set up key bindings like this: 

    (define-key global-map (kbd "C-.") 'blind-up)
    (define-key global-map (kbd "C-,") 'blind-down)

