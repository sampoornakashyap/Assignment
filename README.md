Admin username created using py manage.py createsuperuser
Admin username: sampoorna; admin password: sampoorna
Admin capacities: 
- After Login: Total Number Of Student, Teacher, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete, Approve Teacher.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions and total question numbers To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.
Teacher capacities:
- Signup which when accepted by Admin, Login. This is done to ensure no unverified user can login as teacher. 
- After Login: Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions
Student Capacities: 
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.

Hosted website on Github: https://sampoornakashyap.github.io/Assignment/
Postman Collection: https://www.getpostman.com/collections/e16dfe37452b39a4a489
To open on local server: Install all the requirements>Download this repository as zip and extract it>In your cmd go to the location of the dowloaded file and run the following commands: py maage.py makemigrations // py manage.py migrate // py manage.py runserver> Go to http://127.0.0.1:8000/ in your browser
