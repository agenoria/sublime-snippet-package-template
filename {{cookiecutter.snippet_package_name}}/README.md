# {{cookiecutter.snippet_package_name}} *(v{{cookiecutter.version}})*

{{cookiecutter.project_short_description}}

## Installation

If you're using [Package Control](https://packagecontrol.io/) for Sublime Text, simply install the `{{cookiecutter.snippet_package_name}}` package.

Alternatively, you can clone this repository directly into your Sublime plugin folder and install the snippets manually as described below:

#### OSX

```
cd ~/Library/Application Support/Sublime Text 3/Packages
git clone --depth 1 https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.github_repository}}.git
```

#### Linux (may vary based on distro.)

```
cd ~/.config/sublime-text-3/Packages
git clone --depth 1 https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.github_repository}}.git
```

#### Windows

```
cd "%APPDATA%\Sublime Text 3\Packages"
git clone --depth 1 https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.github_repository}}.git
```

*Note:* If you are having trouble finding the correct location to install the snippets, refer to the [documentation](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-data-directory) on the subject.

## Usage

TODO: add some usage instructions

## Credits

The framework for this package was created from the Sublime Text Snippet Template available here: [https://github.com/agenoria/sublime-snippet-package-template](https://github.com/agenoria/sublime-snippet-package-template).
