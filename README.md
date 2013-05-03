# README

## About

This is a pre commit script that checks added, copied, modified or renamed files for syntax errors and Fork CMS coding standards.

## Dependencies

### php codesniffer

[http://pear.php.net/package/PHP_CodeSniffer/redirected](http://pear.php.net/package/PHP_CodeSniffer/redirected)

You can install php codesniffer with these commands:

	sudo pear update-channels
	sudo pear install PHP_CodeSniffer

### Fork coding standards in ~/.phpcs/Fork

This is based on this dotfiles setup: [https://github.com/WouterSioen/dotfiles](https://github.com/WouterSioen/dotfiles).
If you want to put it in another place, just change the --standard parameter in the phpcs command.

### esvalidate

[https://github.com/duereg/esvalidate](https://github.com/duereg/esvalidate)

Esvalidate is easy to install with the node package manager:

	sudo npm install -g esvalidate

### CSS lint

[https://github.com/stubbornella/csslint/wiki/Command-line-interface](https://github.com/stubbornella/csslint/wiki/Command-line-interface)

CSS Lint is easy to install with the node package manager:

	sudo npm install -g csslint

## Installation

Put the pre-commit file in the .git/hooks/ folder in your git repository.

Don't forget to make the pre-commit file executable

	chmod +x .git/hooks/pre-commit
