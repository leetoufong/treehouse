# The Anatomy of a Component

+ Components are the backbone of building Ng apps
+ Components are made up of Templates, Classes and Decorators

**Component = Template + Class + Decorator**

+ **Templates** is the view or UI for the a component
+ **Class** is the code that brings your template to life
+ **Decorator** is the part that wires up the Class and Template
+ **Components** are made up of 2 properties
  1. `selector` and
  2. `template`
+ It is ideal to use `templateUrl` instead to keep code and template view separate
+ It is best to keep all the styles and files with the component files it relates to
+ You can't assign a `this` on a property without first defining it on a class (outside of the constructor)

  ```
  emoji: string[];
  constructor(){
    this.emoji = [];
  }
  ```

+ **Interpolation** is a form of data binding