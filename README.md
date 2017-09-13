# JDBC exercise

In this repository you'll find the *pom.xml* with all the needed Spring dependencies: you'll see 
dependencies for web, devtools and h2. You also have *schema.sql* and *data.sql* that define a 
table of **classrooms** and insert few classrooms to the table.

You need to program for storing a retrieving classrooms to the embedded H2 database. You'll 
need to create at least the classes **Classroom** and **ClassroomDAO**. I want to be able to
 perform the following operations:
 * Insert a new classroom
 * Insert a set/list of classrooms (with the batchupdate)
 * Delete a classroom
 * Query all classrooms
 * Query the classrooms that have more or less capacity than a given one
 * Query the classrooms depending in whether they have plugs

You also need to test that your classes work properly