## Installation

	$> npm install package.json

In the folder where you installed MJML you can now run:

	$> ./node_modules/.bin/mjml -V

To avoid typing ./node_modules/.bin/, add it to your PATH (add it to .bashrc or .zshrc so you don't have to export it anymore):

	$> export PATH="$PATH:./node_modules/.bin"

You can now run MJML directly, in that folder:

	$> mjml -V

## Usage

To compile, render and redirect the result to a file. If the file does not exist, it will be created.

	$> mjml input.mjml -o my-email.html

or

	$> mjml input.mjml --output my-email.html


Watch changes on a file

	$> mjml -w input.mjml

or

	$> mjml --watch input.mjml


## Documentation

[mjml Documentation](https://mjml.io/documentation)