# README

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

	npm install -g esvalidate

## Installation

Put the pre-commit file in the .git/hooks/ folder in your git repository.
