The depreccated way of using sass with the use of @import which is a traditional way. The dart-sass in the documentation implemented a new rule,using @use and @forward.

This repository is a test on how to use the @use and @forward.

Firstly,

'You need to install in the node package manager (npm). If you don't have it install yet try to follow this link:

https://radixweb.com/blog/installing-npm-and-nodejs-on-windows-and-mac
(I don't own the link)'

and once npm is installed try to install sass globally using this command

'npm install -g sass'
it will install sass globaly meaning you can use it in any folder in your computer

To run SASS:

Type this command to use sass in any files

<!-- If you follow my path directory here's what I do. -->

'sass ./scss/main.scss ./dist/css/style.css'

<!-- You will notice that in the first path the main.scss file that I want them to compile and deliver it to the dist folder and create a file name style.css  -->

<!-- SAMPLE EXPLANATION -->

'sass ./path-to-your/main.scss-file ./path-where-to-compile/style.css'
