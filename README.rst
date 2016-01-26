=================
 pyenv-mode-auto
=================

.. image:: http://melpa.org/packages/pyenv-mode-auto-badge.svg
   :target: http://melpa.org/#/pyenv-mode-auto

Automatically activate pyenv version from Emacs with `pyenv-mode <https://github.com/proofit404/pyenv-mode>`_.

It traverse directories up until ``.python-version`` file will be found and activates pyenv version defined there.

Extracted from my blog post `Automatically activate pyenv version from Emacs <http://ssbb.me/posts/emacs-pyenv-auto-activation-en/>`_.

Installation
============

You can simply install package from `Melpa <https://melpa.org/>`_.

.. code-block:: lisp

   (add-to-list 'package-archives
          '("melpa" . "http://melpa.org/packages/") t)

And then :kbd:`M-x package-install [RET] pyenv-mode-auto [RET]`. After Installing you should `require` this package:

.. code-block:: lisp

   (require 'pyenv-mode-auto)

Usage
=====

Just open any file within you project (with ``.python-version`` file in the same directory or above) and you pyenv version will be activated.
