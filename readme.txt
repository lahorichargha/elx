Internal
========

fixed:           7
false positives: 0

examples fixed
--------------

- :authors    (("Henry Kautz")
-             ("(according to authors.el)"))
+ :authors    (("Henry Kautz"))

;;; bib-mode.el --- major mode for editing bib files

;; Copyright (C) 1989, 2001-2011  Free Software Foundation, Inc.

;; Author: Henry Kautz
;; (according to authors.el)
;; Maintainer: FSF
;; Keywords: bib

----

- :authors    (("Henry Kautz")
-             ("(according to authors.el)"))
+ :authors    (("Henry Kautz"))

;;; dabbrev.el --- dynamic abbreviation package

;; Copyright (C) 1985-1986, 1992, 1994, 1996-1997, 2000-2011
;;   Free Software Foundation, Inc.

;; Author: Don Morrison
;;	Lars Lindberg
;; (according to ack.texi)


External
========

fixed:           29
false positives: 2
still wrong:     1 

false positives
---------------

- :authors    (("Greg Newman" . "grep@20seven.org")
-             ("Guilherme Gondim" . "semente@taurinus.org"))
+ :authors    (("Greg Newman" . "grep@20seven.org"))

;;; dpastede.el --- Emacs integration for dpaste.de

;; Copyright (C) 2008, 2009 Greg Newman <20seven.org>

;; Version: 0.1
;; Keywords: paste pastie pastebin dpaste python
;; Created: 18 Dec 2009
;; Author: Greg Newman <grep@20seven.org>
;; Guilherme Gondim <semente@taurinus.org>
;; Maintainer: Greg Newman <greg@20seven.org>

----

- :authors    (("Shelagh Manton" . "shelagh.manton@gmail.com")
-             ("David F. Skoll"))
+ :authors    (("Shelagh Manton" . "shelagh.manton@gmail.com"))

;;; remind-conf-mode.el --- A mode to help configure remind.

;; Copyright (C) 2008 - 2011  Shelagh Manton <shelagh.manton@gmail.com>

;; Author: Shelagh Manton <shelagh.manton@gmail.com> with help from
;; David F. Skoll
;; Keywords: remind configure convenience



still wrong
-----------

This was wrong before the fix and still is after it.
In other words it is not related to the proposed fix.

- :keywords   ("look-for" "regexp" "list" "regexp" "samples")
+ :keywords   ("look-for" "regexp" "list" "regexp")

;;; anything-project.el -- finding any resource of a project

<snip>

;;; Configuration:
;; you can add new project rule by `ap:add-project' function
;; keywords :look-for, :include-regexp and :exclude-regexp can be regexp or list of regexp
;; below are few samples
