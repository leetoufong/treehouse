# The Importance of Static Typing in Angular

+ Ng is the first major front-end framework
+ TS has all the same syntax as JS

    ```
    class Greeter {
      greet(name: string) {
          console.log(`Hi ${name}`);
      }
    }
    const greeter = new Greeter();
    greeter.greet('Jim'); // Hi Jim
    // greeter.greet(5); // This will not work
    ```

+ Passing in `name: string` prevents the caller from accidentally passing in a value that isn't a string
+ VSCode supports TS out of the box

    ```
    function rollCall(students: any[], max?: number) {
      max = max || students.length
      const attendance = students.slice(undefined, max);
      console.log(attendance);
    }

  rollCall(['Jack', 'Jill']);
    ```

+ **Intellisense** is intelligent code completion aid
+ When the TS popup shows a parameter with `?`, it means that it is optional
+ Various TS value types:
  - `number` represents both integer as well as floating-point numbers
  - `boolean` represents true/false
  - `string` represent a sequence of characters
  - `void` generally used on function return-types
  - `null` when an object does not have any value
  - `undefined`	denotes value given to uninitialized variable
  - `any`	declared for any data-type