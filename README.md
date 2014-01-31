V. I. Arnold: Problems for children from 5 to 15
================================================

This repository contains the LaTeX sources of the translations of Arnolds famous book "Problems for children from 5 to 15" derived from the Russian original http://www.mccme.ru/free-books/izdano/2004/VIA-taskbook.pdf.

![V. I. Arnold](https://raw.github.com/IMAGINARY/Arnold5to15/master/resources/photo-arnold_small.jpg "V. I. Arnold")

The material in this repository is available under the Creative Commons BY-NC-SA 3.0 license (http://creativecommons.org/licenses/by-nc-sa/3.0/)

Compiling the documents
-----------------------

Since the book is available in serveral languages, we decided to use the XeLaTeX engine. It directly supports unicode and eases font loading. This frees us from the usual LaTeX input/font encoding issues. 

You can use the command line
```
xelatex 5to15_xx_XX.tex 
```
where `xx` is the [language code](http://www.langtag.net/registries/lsr-language.txt) and `XX` is the [region code](http://www.langtag.net/registries/lsr-region.txt) to create `5to15_xx_XX.pdf`. Usually, you can also configure the TeX editor of your choice to use XeLaTeX instead of pdfLaTeX.

Note that the documents rely on a number of recent packages. Therefore:

*Please make sure that you are using a relatively recent TeX distribution.*

You can also consult the file `preamble.tex` for a list of used packages. `preamble.tex` is shared by all the different translations.

Contributing
------------

We encourage you to add translations for new languages and to improve existing ones. 

### Adding a translation

### Improving existing translations

### Using git and GitHub

In order to keep track of your changes, we highly recommend using the git version control system on GitHub. Ideally, you will fork this repository into your GitHub account, clone it to your local system, apply your changes to the documents, commit and push everything to GitHub and finally make a pull request so that we can check your modifications and merge them with the master branch.

### New to XeLaTeX, git and GitHub?

Well, learning new tools is always worth it ;-)
