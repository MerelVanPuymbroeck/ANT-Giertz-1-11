# CSS preprocessors

CSS lacks a few features some people might consider paramount. For example, nesting different rules, variables, functions, ...

To add support for these, we can make up new languages and write a program that converts our new and fancy language to plain old CSS.

## Goals

- Being able to explain CSS-Preprocessors
- Knowing 'the big ones'
- Generate some CSS from your CSS preprocessor of choice

## Deadline

About 1 day

## Setup

1. Look up what CSS preprocessors are available.
2. Pick one of these and write down at least 2 reasons why you would pick that one
3. Install the one you picked

## Excercise

1. Create a new repository named `CSS-Preprocessor`
2. Create an `index.html` file to experiment in
3. Create a folder called `assets`
4. Inside that folder, create a folder for each type of asset you will use (images, CSS frameworks, javascript, SASS files, LESS files, Font files, ...)    
Example: ![assets-content](images/assets-content.png)
5. Notice that this is a suggestion, nothing stops you from changing this structure to suit your style
6. Create a SASS/LESS/STYLUS/... file called `assets/<YOUR CHOICE OF PREPROCESSOR>/style.<FILETYPE OF YOUR PREPROCESSOR>`    
For example if you chose SASS, create a file called `assets/sass/style.scss`
7. Configure your project so that your SASS/LESS/STYLUS/... file gets compiled into `assets/css/style.css` each time you change your SASS/LESS/STYLES/... file
8. Link the style.css file
9. Experiment with the features in your choice of preprocessor. For SASS you can check out [this excercise](https://gist.github.com/pixeline/dab8a29566b994453b8c681ed2b7ff2a)


## Project 

1. Pick a previous project
2. Create a branch called `convert-to-YOUR_PREPROCESSOR`
3. Convert to a css preprocessor by using as many new functions: Variables, nesting, comments, ... try to make code reusable.

Tips:    

- Use a value repeatedly? Use variables
- Use complex selectors? Try to nest them
- If you use calculated values like `width: 33%`, calculate them using the full formula `width: (100/3)*1%;`
- Lookup some mixins and use them

Done? Try to merge your new branch into the master.

## Conclusion

Congrats you can now claim to be a SASS/LESS/STYLUS expert.

![sassy](images/sassy.gif)
