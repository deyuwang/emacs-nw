# emacs-nw

Integration nodewebkit and emacs


## Features

 * Auto synchron content between nodewebkit and emacs

## Installation

	(add-to-list 'load-path "~/.emacs.d/emacs-nw")
	(require 'emacs-nw)

## Setup

Edit: `~/.emacs.d/emacs-nw/emacs-nw.el`:

	(defvar temp-file "~/request.html")
	(defvar auto-doc-reg "request\\.html$")
	(defvar base-url "http://127.0.0.1:13678")
	(defvar nw-server-path "~/.emacs.d/emacs-nw/emacs-nw-server") 


## Usage

1.	Call `run-doc-server`
2.	M-x `pull-doc`
3.	Edit something
4.	C-x s (Save)
