# tex-unicodechars

This LaTeX package allows you to use unicode characters in your LaTeX source file.
It provides a long list of \newunicodechar definitions. 
Unicode characters make the source file more readable.
You will need a text editor in which you can enter the characters. 
I use [Vim](https://github.com/vim) for that.

## To entering unicode characters in VIM

you can either use either
* ctrl-V in insert mode (see `:help i_CTRL-V_digit`) 

or its equivalent LaTeX command and one of these:
* [latex-unicoder](https://github.com/joom/latex-unicoder.vim): A plugin to type Unicode chars in Vim (you can switch back and forth between the latex command and its equivalent unicode character)
* [vim-unicode-snippets](https://github.com/danielwe/vim-unicode-snippets): Type Unicode by [Ultisnips](https://github.com/SirVer/ultisnips) snippet expansion of LaTeX keywords
* [julia-vim](https://github.com/JuliaEditorSupport/julia-vim): Vim support for Julia, includes [latex-to-unicode](https://github.com/JuliaEditorSupport/julia-vim#latex-to-unicode-substitutions) substitutions (you can search unicode characters in command mode)
