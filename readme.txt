This is a java program that generates SQL code to check normal form.

This program checks 1NF, 2NF, 3NF and BCNF.

The input is a set of tables(relations) and a potential “candidate key (CK)” for each table(it is initially unknown if the given CK is indeed a CK).

The output consist of: A summary table that states for each table if it complies with BCNF(Y/N), and a
decomposition of the input table into multiple tables when it is not in BCNF and verify the decomposition tables. 


Following are the commands to run the file.
1. export CLASSPATH=$CLASSPATH:/home/y2017/spring/cs6340/team01/vertica-jdk5-6.1.3-0.jar:.
2. java main database=data.txt
