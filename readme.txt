this basic level student database  management with simple comand line tools


this module contains :
	1.add_student()
	2.delete_student()
	3.update()
	4.student_excel()
above functions to create delete,update the the database.



1.add_student():
	adding student details by this method ,it requires one list
 that will contain what you want to store data,Example:
	from Data_base import Database
	list=['age','section','phone']
	s=Database()
	s.add_student(list)
	[Note:adress are allowed in one line]
	
	if you want see or acess student details you can go to database folder and acess the student_data.json

2.delete_student():
	to delete specific student, this method to delete,
	by:
	s.delete_student()
	o/p:Enter student name:arun
	    successfully deleted arun
	it will delete all data you enter student name
3.update():
	if you want add update the data of student you will use this method,
	
	by:
	list=['age',section']
	s.update(list)
	[Note:you will insert another list elements what you want to update]
	
4.student_excel():
	if you want student data in excel form use this method,
	by:
	s.student_excel()
	it will create new worksheet
	[Note:in this method the excel sometimes have irregular spacing,merging in futur i will update ,you can edit manually]


		Thanks for using my project

Created by: S.Arun(arunmass)
student of TEC



any problems you will tell because this is my begginer level project thanking you.....
	
