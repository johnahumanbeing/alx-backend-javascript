# Project: 0x02. ES6 classes

## About
- Class declaration
- Constructors
- Getters & Setters
- Inheritance
- Abstract classes
- ES6 Symbols

## Resources

#### Read or watch:

* [Classes]
* [Metaprogramming]

### Setup

#### Install NodeJS 12.11.x

(in your home directory):
```
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

```
$ nodejs -v
v12.11.1
$ npm -v
6.11.3
```

#### Install Jest, Babel, and ESLint

in your project directory, install Jest, Babel and ESList by using the supplied `package.json` and run `npm install`.

## Configuration Files

Add the files below to your project directory

`package.json`
Click to show/hide file contents

`babel.config.js`
Click to show/hide file contents

`.eslintrc.js`
Click to show/hide file contents

and…
Don’t forget to run `$ npm install` when you have the `package.json`


## Tasks
0. `ClassRoom` class declaration

1. `initializeRooms` function that returns an array of 3 `ClassRoom` objects.

2. `HolbertonCourse` class declaration
    - Implements getter and setter methods for its attributes.

3. `Currency` class declaration
    - Implements getter and setter methods for its attributes.
    - Implements a instance method `displayFullCurrency`

4. `Pricing` class declaration
    - Extends ``Currency` from [3-currency.js](3-currency.js)
    - Implements getter and setter methods for its attributes
    - Implements static method `convertPrice`

5. `Building` class declaration
    - Implements getter for each attribute
    - Serves as an `abstract class`
    - Ensure that extending classes must have `evacuationWarningMessage` method


6. `SkyHighBuilding` class declaration
    - Implements getter for each attribute
    - Overrides `evacuationWarningMessage` method

7. `Airport` class declaration
    - Overrides `Symbol.toStringTag` property

8. `HolbertonClass` class declaration
    - Implements `Symbol.toPrimitive` method

9. Fixing code to handle:
    - Class declaration hoisting
    - Setter and getter methods implementation
    - Exporting variable declaration and values

10. `Car` class declaration
    - Implements getter for `Symbol.species` property.
    - Implements `cloneCar` method.

11. `EVCar` class declaration
    - Extends `Car` class from [10-car.js](10-car.js)
    - Overrides `Symbol.species` to utilize parents constructor method.

## Files

| Task | File |
| ---- | ---- |
| 0. You used to attend a place like this at some point | [0-classroom.js](./0-classroom.js) |
| 1. Let's make some classrooms | [1-make_classrooms.js](./1-make_classrooms.js) |
| 2. A Course, Getters, and Setters | [2-hbtn_course.js](./2-hbtn_course.js) |
| 3. Methods, static methods, computed methods names..... MONEY | [3-currency.js](./3-currency.js) |
| 4. Pricing | [4-pricing.js](./4-pricing.js) |
| 5. A Building | [5-building.js](./5-building.js) |
| 6. Inheritance | [6-sky_high.js](./6-sky_high.js) |
| 7. Airport | [7-airport.js](./7-airport.js) |
| 8. Primitive - Holberton Class | [8-hbtn_class.js](./8-hbtn_class.js) |
| 9. Hoisting | [9-hoisting.js](./9-hoisting.js) |
| 10. Vroom | [10-car.js](./10-car.js) |
| 11. EVCar | [100-evcar.js](./100-evcar.js) |