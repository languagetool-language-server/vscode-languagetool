# LanguageTool Extension for Visual Studio Code - ARCHIVED

## Project Archival

[Adam Voss](https://github.com/adamvoss), originator of this project, passed away on July 11, 2018. I ([David Day](https://github.com/davidlday)) inherited his [languagetool-language-server](https://github.com/languagetool-language-server) projects. I didn't know Adam at all, and I spent about a year trying to figure out what to do with this gift. I've ultimately decided to archive the LanguageTool Extension and related repositories. This extension will no longer be maintained, and will likely be removed from the [Extension Marketplace](https://marketplace.visualstudio.com/). However, I am still pursuing the idea of contributing Adam's server-side LSP code back to the [LangugeTool](https://github.com/languagetool-org/languagetool) project.

Here are some alternative extensions:

1. [LT<sub>E</sub>X](https://github.com/valentjn/vscode-ltex), which is a fork of @adamvoss original work by @valentjn and thus is preserving his code and memory, which was the most important thing that kept me hanging on to these projects.
1. [LanguageTool Linter](), which is a new extension I've authored based on the [Atom Linter LanguageTool]() extension.
1. [languagetool](https://marketplace.visualstudio.com/items?itemName=raymondcamden.languagetool), which I know nothing about.

Good luck, and Peace.

RIP Adam Voss, July 11, 2018.

## Original README

**NOTICE: as of v0.0.2, this extension does not include any languages.  You MUST install a [language support extension][lang-exts].**
___
Provides offline grammar checking in Visual Studio Code using [LanguageTool](https://languagetool.org/) via the [LanguageTool Language Server](https://github.com/adamvoss/languagetool-languageserver).  This extension provides only the core functionality.  You must [install extensions containing the language rules for each language you wish to be able to check][lang-exts].

## Features
* Issue highlighting with hover description.
* Replacement suggestions.
* Checks **plaintext** and **markdown**.
* Support **over than 20 languages** according to which [language support extensions][lang-exts] are installed.

## Requirements
Java 8+ is required.

## Extension Settings

This extension contributes the following settings:

* `languageTool.language`: Set to the short code for the language to check.  For supported languages see the [list of languages at LanguageTool.org](https://languagetool.org/languages/).

## Versioning

LanguageTool for Visual Studio code has adopted the versioning of its LanguageTool dependency.  For example, if this extension has version 3.8.0 it is powered by LanguageTool 3.8.  vscode-languagetool 3.8.1, would also use LanguageTool 3.8.  vscode-languagetool 3.9.0 would use LanguageTool 3.9.  **The LanguageTool version of this extension must match the LanguageTool version of your installed language support extensions.**

## Contributing
Contributions welcome!  
This repository uses git submodules.  After cloning, be sure to run `git submodule update --init`.

## Known Issues
Please report issues or submit pull requests on [GitHub](https://github.com/adamvoss/vscode-languagetool).

[lang-exts]: https://marketplace.visualstudio.com/search?term=LanguageTool&target=VSCode
