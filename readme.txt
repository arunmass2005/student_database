this basic level student database  management with simple comand line tools


this module contains :
	1.add_student()
	2.delete()
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
