# VHS syntax

Sublime Text 4 syntax hightling package for charmbracelet's [VHS](https://github.com/charmbracelet/vhs) tape files.  
File extension: `.tape`  

## Usage

Once installed, the `VHS` syntax will be available in the list of syntaxes.


## Installation

### Using Package Control

If you have [Package Control](https://packagecontrol.io/installation) installed: `Command Palette` → `Install Package` → `VHS`

### Manually

Clone this repository in your local packages folder.  
If you are unsure as to where your local packages directory is, please consult the [docs](https://docs.sublimetext.io/guide/getting-started/basic-concepts.html#the-data-directory).  

Example (on MacOS):

```shell
cd ~/Library/Application\ Support/Sublime\ Text/Packages
git clone git@gitlab.com:patopest/sublime-text-vhs-syntax.git "VHS Syntax"
``` 


## Development

- Clone the repository in your local packages.
- Make edits to the `.sublime-syntax` files, the syntax reloads on save.

### Tests

- Any file with the names starting with `syntax_test_` can be used as a test.
- Open the file and run `Tools > Build` (or `CMD`+`B` on macOS).

Sublime's docs about test files: [here](https://www.sublimetext.com/docs/syntax.html#testing)


### Useful documentation:
- [VHS](https://github.com/charmbracelet/vhs)
- [Sublime Syntax Definitions](https://www.sublimetext.com/docs/syntax.html#testing)
- [Sublime Syntax Scopes](https://www.sublimetext.com/docs/scope_naming.html#)