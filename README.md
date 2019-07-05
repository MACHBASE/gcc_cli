# gcc_cli
This sample is for compiling the linux based cli sample source with gcc.

<hr/>

# How to use
<hr/>
1. insert command "git clone https://github.com/KoreaLSH/gcc_cli.git" to download files.
  
2. insert command "make" to compile *.c files.

3. Try to execute sample files.


#Instruction
<hr/>

**1. Makefile**  
compile file

**2. make_data.c**  
create data.txt file for sample4_append2 case

**3. make_suffle_data.c**  
create data files for sample8_multi_session_multi_table case

**4. sample1_connect.c**  
connect with Machbase server

**5. sample2_insert.c**  
direct insert and retrieve data from table

**6. sample3_prepare.c**  
prepare insert and retrieve data from table

**7. sample4_append1.c**  
insert data with high speed input protocol.

**8. sample4_append2.c**  
read data from text file and insert data with high speed input protocol.

**9. sample5_describe.c**  
get column information with SQLDescribeCol().

**10. sample6_columns.c**  
get column information with SQLColumns().

**11. sample8_multi_session_multi_table.c**  
read data files and insert data with multi thread.
