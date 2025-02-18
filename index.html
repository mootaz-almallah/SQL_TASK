CREATE TABLE `azooz`.`courses` (`course_id` INT(10) NOT NULL , `course_name` VARCHAR(10) NOT NULL , `course_code` INT(10) NOT NULL , `credit` VARCHAR(10) NOT NULL , `department` VARCHAR(10) NOT NULL , PRIMARY KEY (`course_id`)) ENGINE = InnoDB; 


CREATE TABLE `azooz`.`instructors:` (`instructor_id` INT NOT NULL , `first_name` VARCHAR NOT NULL , `last_name` VARCHAR NOT NULL , `email` VARCHAR NOT NULL , `hire_date` DATE NOT NULL , `department` VARCHAR NOT NULL , PRIMARY KEY (`instructor_id`)) ENGINE = InnoDB; 


CREATE TABLE `azooz`.`enrollments` (`enrollment_id` INT(10) NOT NULL , `student_id` INT(10) NOT NULL , `course_id` INT(10) NOT NULL , `grade` VARCHAR(10) NOT NULL , PRIMARY KEY (`enrollment_id`)) ENGINE = InnoDB; 

CREATE TABLE `azooz`.`course assignments` (`assignment_id` INT NOT NULL , `instructor_id` INT NOT NULL , `course_id` INT NOT NULL , `semester` VARCHAR NOT NULL , `year` INT NOT NULL , PRIMARY KEY (`assignment_id`)) ENGINE = InnoDB; 


INSERT INTO Students (first_name, last_name, email, date_of_birth, gender, major, enrollment_year) VALUES
('Ali', 'Khalid', 'ali.khalid@example.com', '2001-05-12', 'Male', 'Computer Science', 2020),
('Mona', 'Salih', 'mona.salih@example.com', '2000-08-22', 'Female', 'Mathematics', 2019),
('Ahmed', 'Hassan', 'ahmed.hassan@example.com', '2002-02-15', 'Male', 'Physics', 2021),
('Sara', 'Ibrahim', 'sara.ibrahim@example.com', '2001-07-09', 'Female', 'Engineering', 2020),
('Omar', 'Nasser', 'omar.nasser@example.com', '1999-12-25', 'Male', 'Business', 2018),
('Lina', 'Ziad', 'lina.ziad@example.com', '2003-04-18', 'Female', 'Chemistry', 2022),
('Hussein', 'Mohammed', 'hussein.mohammed@example.com', '2000-09-30', 'Male', 'Medicine', 2019),
('Fatima', 'Adnan', 'fatima.adnan@example.com', '2001-11-11', 'Female', 'Biology', 2020),
('Jamal', 'Tariq', 'jamal.tariq@example.com', '2002-06-05', 'Male', 'Economics', 2021),
('Rania', 'Fadel', 'rania.fadel@example.com', '2000-03-17', 'Female', 'History', 2019);

-- إدخال البيانات في جدول الدورات
INSERT INTO Courses (course_name, course_code, credits, department) VALUES
('Database Systems', 'CS101', 3, 'Computer Science'),
('Linear Algebra', 'MATH201', 4, 'Mathematics'),
('Quantum Physics', 'PHYS301', 3, 'Physics'),
('Thermodynamics', 'ENG202', 3, 'Engineering'),
('Business Management', 'BUS101', 3, 'Business');

-- إدخال البيانات في جدول المدرسين
INSERT INTO Instructors (first_name, last_name, email, hire_date, department) VALUES
('Salim', 'Karim', 'salim.karim@example.com', '2010-09-01', 'Computer Science'),
('Nada', 'Othman', 'nada.othman@example.com', '2015-06-15', 'Mathematics'),
('Tariq', 'Jamal', 'tariq.jamal@example.com', '2012-04-10', 'Physics'),
('Hana', 'Fawzi', 'hana.fawzi@example.com', '2018-11-20', 'Engineering'),
('Othman', 'Saad', 'othman.saad@example.com', '2009-02-25', 'Business');

-- تعيين المدرسين للدورات
INSERT INTO CourseAssignments (instructor_id, course_id, semester, year) VALUES
(1, 1, 'Fall', 2024),
(2, 2, 'Spring', 2024),
(3, 3, 'Fall', 2024),
(4, 4, 'Spring', 2024),
(5, 5, 'Fall', 2024);

-- تسجيل الطلاب في الدورات (كل طالب مسجل في دورتين على الأقل)
INSERT INTO Enrollments (student_id, course_id, grade) VALUES
(1, 1, 'A'), (1, 2, 'B'),
(2, 3, 'B'), (2, 4, 'A'),
(3, 5, 'C'), (3, 1, 'A'),
(4, 2, 'B'), (4, 3, 'A'),
(5, 4, 'C'), (5, 5, 'B'),
(6, 1, 'A'), (6, 2, 'B'),
(7, 3, 'C'), (7, 4, 'B'),
(8, 5, 'A'), (8, 1, 'C'),
(9, 2, 'B'), (9, 3, 'A'),
(10, 4, 'C'), (10, 5, 'B');


SELECT `student_id`, COUNT(`student_id`) FROM students GROUP BY `student_id`;
SELECT COUNT(*) AS total_courses FROM Courses;

SELECT S.first_name, S.last_name FROM Students S
JOIN Enrollments E ON S.student_id = E.student_id
WHERE E.course_id = (SELECT course_id FROM Courses WHERE course_name = 'Quantum Physics');

SELECT email FROM Instructors WHERE department = 'Computer Science';


SELECT C.course_name, COUNT(E.student_id) AS enrolled_students
FROM Courses C
LEFT JOIN Enrollments E ON C.course_id = E.course_id
GROUP BY C.course_name;


---------------------------------------------------------------------------------------------------------------------
SELECT C.course_name, I.first_name, I.last_name
FROM CourseAssignments CA
JOIN Courses C ON CA.course_id = C.course_id
JOIN Instructors I ON CA.instructor_id = I.instructor_id
WHERE CA.semester = 'Fall' AND CA.year = 2024;





SELECT C.course_name, AVG(CASE 
    WHEN E.grade = 'A' THEN 4.0 
    WHEN E.grade = 'B' THEN 3.0 
    WHEN E.grade = 'C' THEN 2.0 
    ELSE 0 END) AS average_grade
FROM Courses C
JOIN Enrollments E ON C.course_id = E.course_id
WHERE C.course_name = 'Database Systems'
GROUP BY C.course_name;


































<?php

// $host = "localhost"; 
// $user = "root"; 
// $password = ""; 
// $database = "azooz";
// try {
//     $conn = new PDO("mysql:host=$host;dbname=$database;charset=utf8", $user, $password);

//     echo "تم الاتصال بنجاح! يا كبير <br>";

// //     INSERT INTO azooz (first_name, last_name, email, date_of_birth, gender, major, enrollment_year) VALUES
// // ('Ali', 'Khalid', 'ali.khalid@example.com', '2001-05-12', 'Male', 'Computer Science', 2020),
// // ('Mona', 'Salih', 'mona.salih@example.com', '2000-08-22', 'Female', 'Mathematics', 2019),
// // ('Ahmed', 'Hassan', 'ahmed.hassan@example.com', '2002-02-15', 'Male', 'Physics', 2021),
// // ('Sara', 'Ibrahim', 'sara.ibrahim@example.com', '2001-07-09', 'Female', 'Engineering', 2020),
// // ('Omar', 'Nasser', 'omar.nasser@example.com', '1999-12-25', 'Male', 'Business', 2018),
// // ('Lina', 'Ziad', 'lina.ziad@example.com', '2003-04-18', 'Female', 'Chemistry', 2022),
// // ('Hussein', 'Mohammed', 'hussein.mohammed@example.com', '2000-09-30', 'Male', 'Medicine', 2019),
// // ('Fatima', 'Adnan', 'fatima.adnan@example.com', '2001-11-11', 'Female', 'Biology', 2020),
// // ('Jamal', 'Tariq', 'jamal.tariq@example.com', '2002-06-05', 'Male', 'Economics', 2021),
// // ('Rania', 'Fadel', 'rania.fadel@example.com', '2000-03-17', 'Female', 'History', 2019);
// //     ]);

//     echo "تمت إضافة المستخدم بنجاح! <br>";

//     $sql = "SELECT name, age, gpa FROM azooz";
//     $stmt = $conn->query($sql);
    
//     if ($stmt->rowCount() > 0) {
//         echo "<table border='1'>
//                 <tr>
//                     <th>الاسم</th>
//                     <th>العمر</th>
//                     <th>المعدل</th>
//                 </tr>";

//         while ($row = $stmt->fetch(PDO::FETCH_ASSOC)) {
//             echo "<tr>
//                     <td>" . htmlspecialchars($row["name"]) . "</td>
//                     <td>" . htmlspecialchars($row["age"]) . "</td>
//                     <td>" . htmlspecialchars($row["gpa"]) . "</td>
//                   </tr>";
//         }
//         echo "</table>";
//     } else {
//         echo "لا توجد بيانات.";
//     }

// } catch (PDOException $e) {
//     die("فشل الاتصال بقاعدة البيانات يا غالي: " . $e->getMessage());
// }

// $conn = null;
?>
