# Exercise - SQL-view
* before doing this exercise, you have to complete before the following exercises:
  * `0-SQL-installation-and-user-permissions`
  * `SQL-table`
  * `SQL-Select`
  * `SQL-alter`
* create a class `Student` that has:
  * 2 string properties:
    * `name`
    * `surname`
  * a constructor for setting the 2 values
  * getters methods
* use *JDBC* for executing the following queries on the `jdbc:mysql://localhost:3306/newdb` database:
  * create a view `italian_students` that gets all the name and surname of the Italian students
  * create a view `german_students` that gets all the name and surname of the German students
  * execute a select using the the `italian_students` and put the result in an `ArrayList` of `Student` objects called `italianStudents`
  * execute a select using the the `german_students` and put the result in an `ArrayList` of `Student` objects called `germanStudents`
