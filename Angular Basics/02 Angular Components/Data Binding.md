# Data Binding

+ **Data Binding** is the ability to pass data between component `Class` and the `Template`
+ There are 3 ways to pass data 
  1. **One-Way Binding** is data from component property is passed to the view
  2. **One-Way Binding** an event that triggers data being passed from UI into the Class
  3. **Two-Way Binding** is where data is passed between Class and Template or vice-versa
+ **Interpolation** is where brackets are wrapped around a property or an expression

+ Examples of **One-Way Class to Template**

  ```
  <h1>{{ expression }}</h1>
  // Attribute binding
  <input [target]="expression" />
  ```

+ Example of **One-Way Template to Class**

  ```
  <button (event)="expression"></button>
  ```

+ Example of **Two-Way Between Class and Template**

  ```
  <input [(target)]="expression" />
  ```