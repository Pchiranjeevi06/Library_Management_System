# In MYSQL :
create a database using the name given by you. (Here is My database name ---> "project" as you can see any one of the figures)

By using that database to create Tables 1)"book_info"  2)"user_info".

after that, you should select check boxes as per the below figures


# book_info

![book_info](https://github.com/Pchiranjeevi06/Library_Management_System/assets/90667579/68eb1534-95ff-4142-9ec3-eefbc9c38315)

# user_info

![user_info](https://github.com/Pchiranjeevi06/Library_Management_System/assets/90667579/92e2ea60-5fc4-411b-a029-4344bf6411b4)

# Library_Management_System
syntax for connection between MySQL and Java (JDBC):

   try{
	     Class.forName("com.mysql.cj.jdbc.Driver");
	     con = DriverManager.getConnection("jdbc:mysql://localhost:3306/project", "root","#######"); // your mysql password
	 }
         
Note :
here => Username -> root ,, password -> ########  (as per my MySQL Account)

while you implement this code in Eclipse IDE we make sure to connect to the database with MySQL

After creating features as per the record table CHECK Columns names given database which should be the same in the Java file 
