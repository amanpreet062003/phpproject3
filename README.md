


To set up and run the provided SQL code in phpMyAdmin, follow these steps:

Start XAMPP and Services:

Open XAMPP Control Panel. Start the Apache server and MySQL service by clicking the "Start" button next to their respective names. Access phpMyAdmin:

Open your web browser and go to http://localhost/phpmyadmin/. Create a New Database:

Click on the "Databases" tab in phpMyAdmin. Enter a database name (e.g., university_registration) in the "Create database" field. Click the "Create" button. Run the SQL Code:

Select the newly created database from the left sidebar. Click on the "SQL" tab in the top menu. Paste the provided SQL code into the SQL query box. Click the "Go" button to execute the SQL code. This will create the courses table and insert sample data. Verify the Database:

Go back to the "Databases" tab and select your database from the list. Click on the "Tables" tab to see if the courses table was created successfully.

sql code :- ( CREATE TABLE students ( id int(100) NOT NULL AUTO_INCREMENT, name varchar(100) NOT NULL, email varchar(100) NOT NULL, password varchar(100) NOT NULL, image varchar(100) NOT NULL, PRIMARY KEY (id) ) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=utf8mb4

CREATE TABLE IF NOT EXISTS contact_messages ( id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255) NOT NULL, email VARCHAR(255) NOT NULL, message TEXT NOT NULL, created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ); CREATE TABLE IF NOT EXISTS courses ( course_id INT AUTO_INCREMENT PRIMARY KEY, course_name VARCHAR(255) NOT NULL, description TEXT NOT NULL, max_capacity INT NOT NULL );

INSERT INTO courses (course_name, description, max_capacity) VALUES ('Introduction to Programming', 'Learn the basics of programming.', 50), ('Web Development', 'Learn to build websites.', 40), ('Database Management', 'Learn about databases.', 30), ('Data Structures and Algorithms', 'Learn advanced programming concepts.', 20);

)





![Screenshot from 2024-04-13 17-17-56](https://github.com/amanpreet062003/phpproject3/assets/146962888/89600d79-0629-4eb9-8dcd-c5670ee37974)
![Screenshot from 2024-04-13 17-17-45](https://github.com/amanpreet062003/phpproject3/assets/146962888/ad6383bb-724f-424c-a171-3620b4d69690)
![Screenshot from 2024-04-13 17-17-36](https://github.com/amanpreet062003/phpproject3/assets/146962888/f8a922c2-ca47-425b-bdb6-136f98a4260f)
![Screenshot from 2024-04-13 17-17-26](https://github.com/amanpreet062003/phpproject3/assets/146962888/f69295bd-1014-443b-8a60-2c88bb6a9d43)
![Screenshot from 2024-04-13 17-15-01](https://github.com/amanpreet062003/phpproject3/assets/146962888/89e57b55-1e5c-4b03-ab0f-55491465b425)
![Screenshot from 2024-04-13 17-14-54](https://github.com/amanpreet062003/phpproject3/assets/146962888/ed01299e-3eac-4921-a6a0-1be8e190b060)
![Screenshot from 2024-04-13 17-14-50](https://github.com/amanpreet062003/phpproject3/assets/146962888/fcc2789d-60fc-4a2b-bfcb-3abbccc565bb)
![Screenshot from 2024-04-13 14-25-15](https://github.com/amanpreet062003/phpproject3/assets/146962888/3f6ef1c8-9490-4602-a204-7d7a82f8c969)
![Screenshot from 2024-04-13 14-25-08](https://github.com/amanpreet062003/phpproject3/assets/146962888/881fbeb8-7245-4550-ac65-bef53960fcf5)
![Screenshot from 2024-04-13 14-24-16](https://github.com/amanpreet062003/phpproject3/assets/146962888/7cdde346-0962-48e2-a4bc-e272457d2746)
