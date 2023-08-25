# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > allows for use of parameters in other parts of parts of our backend such as controllers and models

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > member inheritence takes in all public and internal members of a class but not private

3. How does ***accessibility*** affect inheritance?

  > it will dictate what can and cant be accessed 

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > primary key is the identifier for the row in the sql table

5. What is an ***alias***?

  > typically is a different name for a table 

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > SELECT patients.* , patient_doctors.* FROM patients JOIN patient_doctors ON patient_doctors.doctorId = @doctorId WHERE patients.id = patient_doctors.patientId
