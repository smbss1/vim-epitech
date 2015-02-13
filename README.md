vim-epitech
===========

An all-in-one configuration to ease (n)vim usage at Epitech.

## Headers

### Login

Your login is fetched from the environnement: `$USER`. You can override this in your `.vimrc` with `let g:epi_login = 'logi_n'`.

### Full name

For your name, it is fetched from your `finger` information (_Full name_ field). You can change this information in your DE configuration manager or in cli with [`chfn`](http://linux.die.net/man/1/chfn). As for the login you can override this value in your `.vimrc` with `let g:epi_name = 'Nils Logi'`.

## Checker

By default the checker is called with `epinorme <file>`. Program used can be override with `g:epitech_checker_bin`.
