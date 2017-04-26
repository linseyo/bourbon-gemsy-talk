# Bourbon
A simple & lightweight mixin library for SASS (a CSS compiler)
Includes a variety of SASS mixins to make it easier to work with CSS
Makes it easier to add CSS through SASS
## Install:
```
gem install bourbon
```
Rename our application.css to be .scss
```
app/assets/stylesheets/application.scss
```
Delete sprocket
```
*= require_tree .
```

Include bourbon + any other stylesheets at the top of the new application.scss
```
@import "bourbon";
@import "NAMEOFOTHERSTYLESHEETS";
```
### Using Bourbon + Other Fun Stuff:
Bourbon is apart of a bigger family of SASS tools
*Neat <--Bourbon Grid Framework
*Bitters <--Scaffold, Styles & Structures
*Refills <--Components & Patterns for Bourbon
### Resources:
* [Bourbon-Docs]
* [Bourbon-Github]
* [Info On Sass]

[Bourbon-Docs]: <http://bourbon.io/>
[Info On Sass]: <https://www.sitepoint.com/architecture-in-sass/>
[Bourbon-Github]: <https://github.com/thoughtbot/bourbon>

### Example:
my_blog rails app
