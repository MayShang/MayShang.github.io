# refer to gitbook official guide

[gitbookIO](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md)

# Step1: Install nodejs

[download nodejs](https://nodejs.org/en/download/)

# Step2: Install gitbook via NPM
```
$ npm install gitbook-cli -g
```

gitbook-cli is an utility to install and use multiple version of gitbook on the same system. It will automatically install the required version of gitbook to build a book. 

# Step3: Create a book

goto one path and create a new book folder, then

```
$ gitbook init
```
# Step4: Preview book
```
$ gitbook serve
```

or 
# Step5: Build the static website html
```
$ gitbook build
```
