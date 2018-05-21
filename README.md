## Sass & Scss

### Read
- [Sass Basics](https://intranet.hbtn.io/rltoken/CoWVXrIxL8FwCkzcTnYOnw)
- [Sass control directives: @if, @for, @each and @while](https://intranet.hbtn.io/rltoken/-YOCzhIqX1QV_Wpxm-DqQQ)

### References:
- [Sass references](https://intranet.hbtn.io/rltoken/ahyKcZsDBsxjpMANqinZBA)
- [The Sass Way](https://intranet.hbtn.io/rltoken/hWUCTOThzw9DvWmXBLSXPg)
- [Implementing Bubble Sort With Sass](http://thesassway.com/advanced/implementing-bubble-sort-with-sass)
- [Sorting Function](https://css-tricks.com/snippets/sass/sorting-function/)

### What you should learn from this project

- What Sass means
- How to write Sass & Scss file
- What is the difference between Sass and Scss
- What is the Sass preprocessing
- How to declare a variable
- How to use nested definition
- How to import a Sass file
- How to use mixins
- How to declare extend/inheritance styles
- How to manipulate operators

### Comments for your Scss file:

All your Scss file must start with a comment block
```
$ cat my_styles.scss
/* My style */
body {
    .container {
        color: #3D3D3D;
    }
}
$
```
### Install Sass/Scss on Ubuntu 14.04 LTS
```
$ curl -L https://get.rvm.io | bash -s stable

$ source ~/.rvm/scripts/rvm
$ echo "source ~/.rvm/scripts/rvm" >> ~/.bashrc
or
$ source /usr/local/rvm/scripts/rvm 
$ echo "source /usr/local/rvm/scripts/rvm" >> ~/.bashrc

$ rvm install 2.3.1
$ rvm use 2.3.1 --default
$ gem install sass
$ sass --version
Sass 3.5.1 (Bleeding Edge)
```
