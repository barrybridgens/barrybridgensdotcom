---
title: "Spacemacs"
date: 2020-12-06T11:57:57Z
draft: false
---
I have been using emacs for a long time but recently I started playing with an emacs configuration called [spacemacs](https://www.spacemacs.org/)

Spacemacs is an "opinionated" configuration that comes with a large number of packages installed "out of the box". It allows
additional packages to be installed but these are normally specified via "configuration layers" of related package designed to give specific functionality.

The most noticeable aspect of spacemacs is that, by default, it uses the emacs evil-mode package to give vim key bindings. Spacemacs uses the **space**
key as the "leader" key to trigger commands, hence the name. Many of the "normal" emacs "key cord" bindings are also available.

Below is a screenshot of my spacemacs with an org-mode file open.

![org-mode file in spacemacs](/images/spacemacs-org-mode.png)

Pressing the space key gives a list of general commands that can be executed by pressing the keys shown

![spacemacs space options](/images/spacemacs-space-options.png)

Pressing the comma key gives a list of mode specific commands that can be executed by pressing the keys shown

![spacemacs comma options](/images/spacemacs-comma-options.png)

I am using spacemacs in preference to "vanila" emacs because I like the power of the vim key bindings even though I still forget to go into
insert mode before starting to type sometimes. Using the vim key bindings also makes it **much** easier to use (text mode) emacs on a
remote server from a mobile device. Using control and alt key based key cords on a phone or tablet on-screen keyboard is very painful.

... and that is my basic introduction to spacemacs.
