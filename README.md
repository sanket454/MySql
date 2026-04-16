# MySql

Student Course Enrollment System – SQL Mini Project

Description

This project manages student enrollment, courses, exams, and results using SQL.

Tables

* Students
* Courses
* Enrollment
* Exams
* Results

Features

* Student enrollment tracking
* Exam and results management
* Grade calculation
* Data analysis using SQL queries

Example Query

```sql
SELECT c.course_name, AVG(r.marks)
FROM results r
JOIN exams e ON r.exam_id = e.exam_id
JOIN courses c ON e.course_id = c.course_id
GROUP BY c.course_name;
```
 Conclusion

This project demonstrates SQL joins, aggregation, filtering, and real-world database design.
