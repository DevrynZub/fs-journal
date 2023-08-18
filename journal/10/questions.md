# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > namespace is used as an export, it tells other parts of your code what it can use 

02. What is the difference between a `class` and an `interface`?

  > a class represents an object while an interface contains what that class is going to do. 

03. What is the method that returns an instance of a class, yet it has no return type?

  > constructor

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > public

06. In the Car example what is `string` an indication of?

  > the string is going to be used to store data about the car

07. In the Car example what is `abstract` preventing?

  > abstract is used when you are not going to implement it, basically is is used like a virtual

08. In a SQL table, what is the difference between information in a row and information in a column?

  > rows hold information about the single item in that row where a column is a set of data around a certain type. 

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE characters (
  id int NOT NULL,
  name varchar(255) NOT NULL,
  age varchar(255) NOT NULL,
  description varchar(255) NOT NULL
);

10. In SQL how can you query more than a single table? Provide an example.

  > using select allows you to query more then one table. such as the way we are doing ALLSPICE with recipes and ingredients. 
