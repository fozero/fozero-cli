# fozero-cli
> A light tool to generate projects in an easy way，you can choise the template with you like.

# Installation
```
npm install -g fozero-cli
```
or
```
git clone https://github.com/fozero/fozero-cli.git

cd fozero-cli && npm install

npm link
```

# Usage
Open your terminal and type fozero or fozero -h , you'll see the help infomation below:
```
$ fozero

  Usage: fozero <command>

  Options:

    -V, --version  output the version number
    -h, --help     output usage information

  Commands:

    add|a          Add a new template
    init|i         Generate a new project
    list|l         List all the templates
    delete|d       Delete a template
```


Example:

list the template
```
$ fozero list
{ 'template-gulp':
   { url: 'https://github.com/fozero/template-gulp.git',
     branch: 'master' } }
```

generate a project
```
$ fozero init
Template name: template-gulp
Project name: yd-page

 Start generating...

 √ Generation completed!

 cd yd-page && npm install
```


# Official Templates
All official project templates are repos in the [https://github.com/fozero](https://github.com/fozero)
You can run `fozero list` to see all available official templates.

Current available templates include:

- [template-gulp](https://github.com/fozero/template-gulp) - A gulp automated build project template, support for less compile, html, css, js files and image compression, automatically add browser prefix, file browser automatically refresh the local development environment.


# License
MIT.

# Contact
- 如有问题，欢迎给我提[issues](https://github.com/fozero/fozero-cli/issues)
- [https://github.com/fozero](https://github.com/fozero)