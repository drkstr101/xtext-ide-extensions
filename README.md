# Xtext IDE Extensions
This project contains several IDE extensions for the Xtext grammar language, mainly for *VSCode* and *Theia*/*Gitpod* editors. Each one located at its own sub directory.

## List of Supported Extensions

* VS Code (syntax highlighting, folding, brackets)
* Theia/Gitpod (syntax highlighting, folding, brackets)

## Development Hint

All extensions are mainly based on "grammars" for synatx highlighting which have been written using the syntax hightlighting "grammar" online editor [*Iro*](https://eeyo.io/iro/) capable to issue "grammars" for Textmate, Atom, Sublime and others. For details see Chris Ainsley's [article](https://medium.com/@model_train/creating-universal-syntax-highlighters-with-iro-549501698fd2) on it.

In case of Textmate *Iro* creates .plist files. As it is more convinient and more common to use Textmate grammars in JSON format, the .plist file has been transformed using the service http://json2plist.sinaapp.com/.

The *Iro* base file for all extension may be found in the root of the project: *Xtext.iro*.

Contributions are wellcome. Please try to use the *Iro* file and its [editor](https://eeyo.io/iro/) to ensure all extension benefit from in case the syntax highlighting is improved.

For a good starting point highlighting scripts are provided in this repository for

* ACE editor
* Atom editor

*Iro* supports further editor highlighting mechanism and creates appropriate files for it. Take it as a starting point. Support edior highlighting mechamisms are

* Pygments
* Rouge
* Sublime 3
