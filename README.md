This repository includes a java file, in which exists a code for Hotel reservation system made purely upon the foundations of JDBC and MySql database and offcourse core java. 
To run this file you gotta have a Mysql connector JAR file which you can download from the web. Then you will have to include that file in you referenced libraries of your respected code editor's Java Prject. 
For this project i have used java projet with no tools, you can even use maven or gradle for instance. Either way you gotta have the connector file ready in order to run this code.


You also got to have Mysql workbench installed in your dekstop. You need to have a root username and root password to your MySql server client which you have to update in the Hotel Reservation code in order to connect
it with your very own MySql server.
then you have to create a database named "hotel_db" in which you have to have a table named "reservations" with following credentials 
+------------------+--------------+------+-----+-------------------+-------------------+
| Field            | Type         | Null | Key | Default           | Extra             |
+------------------+--------------+------+-----+-------------------+-------------------+
| reservation_id   | int          | NO   | PRI | NULL              | auto_increment    |
| guest_name       | varchar(255) | NO   |     | NULL              |                   |
| room_number      | int          | NO   |     | NULL              |                   |
| contact_number   | varchar(10)  | NO   |     | NULL              |                   |
| reservation_date | timestamp    | YES  |     | CURRENT_TIMESTAMP | DEFAULT_GENERATED |
+------------------+--------------+------+-----+-------------------+-------------------+
Above i have described the table which you will have to create before running the java file in order for it to fetch and enter data in the reservations table.
After doing all this you are all good to run and understand the code in order to better understand JDBC and MySql concepts.
