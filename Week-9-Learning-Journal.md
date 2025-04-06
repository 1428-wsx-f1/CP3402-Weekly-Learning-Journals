# Week 9 Learning Journal

## Learning Activities And Resources
- Lecture
- Lecture Recordings
- [W3Schools - SASS](https://www.w3schools.com/sass/default.php)
- [SASS Documentation](https://sass-lang.com/documentation/)
- [CSS Preprocessors - Sass vs Less](https://www.keycdn.com/blog/sass-vs-less#:~:text=Ashley%20Nolan%20polled%20developers%20in,while%20Less%20received%20140%20votes.)



## Estimated Hours
This week I spent 3.5 hours learning for this subject.


## Content Insights
SASS stands for syntactically awesome styling sheets, as a .scss (sassy cascading style sheet) file type. Since browsers can only read in CSS code, SASS has to be converted to CSS using a file watcher either one time or 
continuously. IDE's (integrated development environment) such as PHPStorm have built-in file watchers, those that don't can make use of separate task runners such as Grunt or Gulp. These task runners are responsible for 
pre-processing and converting SASS to CSS, compiling, postprocessing etc.

SASS' main purpose is to improve the developers experience through a much simpler and manageable stylesheet syntax. This syntax provides more power with pre-processing (allowing use of functions, variables, mixins, 
inheritance etc) to solve common CSS issues including: DRY (don't repeat yourself), find and replace, calculations, changing browser support etc.

SASS variables are denoted with a $ symbol and allow the storage of common data types (e.g. strings, numbers, colours, bool etc.). Extensible variable naming is important to ensure code readability/maintainability. 

SASS features a number of built-in functions to allow for re-usable complex operators. These functions can have variables passed as parameters in order to perform actions including: lighten (colour, amount), function-exists(functionname) 
simple-selectors(selectors), map-get(map, key), index(list, value), abs(number), quote(string) etc.

SASS allows the use of partials. This means that developers can have multiple .scss files, including an underscore for naming. For example, _colours.scss. Using @include, multiple .scss files can build one single CSS file and requires only 
one HTTP request. Partials allow modulularisation of stylesheet code, this greatly improves code readability/maintainability and website performance. Colour, layout and font modifications can be seperated to make desired changes easier, rather than in the same file.

Nesting is included in SASS and written similar to HTML hierarchy. For example, header -> nav -> a (where -> represents an additional level of nesting). This better distinguishes each element of the header for better code structure.

Extend/Inheritence can be used when a class needs to inherit the properties of another class, whilst including its own individual styles. When one class extends another, SASS will ensure all elements in the extendor match the extending class. For example, an 
error message can extend the message class to inherit its properties then apply its own style (such as the colour red).

Mixins allow the defining of CSS styles that can be re-used. Mixins contain style rules that other classes can call using @include and can also accept parameters. Using mixins is highly advantageous for following the DRY principle


## Career/Employability/Learning Insights
SASS is a stylesheet language in growing demand with Bootstrap, WordPress, Zurb, Microsoft Teams, Zoom, Slack and many more. In a poll conducted by Ashley Nolan, 689 (66%) of developers voted Sass as their preferred CSS pre-processor. 
Compared to Less with >140 votes (13.4%), [Jackson, 2023](https://www.keycdn.com/blog/sass-vs-less#:~:text=Ashley%20Nolan%20polled%20developers%20in,while%20Less%20received%20140%20votes.). Google Trends also indicates far more activity regarding SASS compared to Less. This week I learned the basics of SASS which is useful in securing web development jobs. With research I was able to 
find several jobs that require knowledge in CSS pre-processors including SASS. Some of these jobs include: Full Stack Web Developer, Digital Web Developer - WordPress Specialist, React Web Developer, Test Analyst and even a Software Engineer job. 
This indicates that profiency in SASS is a highly sort after and relevant skill in the IT industry. 
