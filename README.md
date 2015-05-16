# simplePlugin
How simple can plugins be?

Install this plugin with the following command:

```
jspm install simplePlugin=github:curran/simplePlugin -o "{ main: 'main.js', format: 'amd' }"
```

Here's how this repository was created:

```
git clone git@github.com:curran/simplePlugin.git
cd simplePlugin/
ls
vim main.js # Write an AMD module
vim README.md # Add the install script snippet
git tag -a v0.0.1 -m "First release"
git push --tags
```
