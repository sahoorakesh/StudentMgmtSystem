# StudentMgmtSystem
Project for Student Management System and use of CURD Operation
//first yo need to create a schema name student_details and give your db username and password
//CreateStudent creates student POST REQUEST
http://localhost:8090/create

//GetAllStudent to get all student data GET REQUEST
http://localhost:8090/get

//GetStudentByID returns Student with specific ID GET REQUEST
http://localhost:8090/get/4


//update student by id
http://localhost:8090/update/id


//Delete student by id
http://localhost:8090/delete/4

//BODY INPUT
  {
        "Id": 4,
        "studentName": "Rahul",
        "grade": "C",
        "classDetails": "ECE"
    }
