# Game Templates for Arcade

This repository stores game templates for the `arcade` using the `cookiecutter` library. These templates can be used 2 ways:
1. Install the `cookiecutter` package and use that to install any of these templates yourself.
1. Use the **arcade** command within the `arcade` library to access the current list of templates available in this repository.

## Installing templates manually
1. Follow the installation instructions for [cookiecutter][ccdocs] then return here.
2. Use the cookiecutter command to install the desired template
```sh
$ cookiecutter install https://github.com:pythonarcade/template.git
```
3. Choose a template from the list and fill in the information requested

## Using acrade to install templates
Make sure you have the [arcade][arcadedocs] package installed
1. run the arcade command to install templates
```sh
$ arcade template
```


<!-- Links -->
[ccdocs]: https://cookiecutter.readthedocs.io/ "Cookiecutter Docs"
[arcadedocs]: https://api.arcade.academy/en/stable/install/index.html "Arcade Install Instructions"