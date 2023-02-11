# Exercise - 10
# Structures and File-IO

This exercise is to understand how to take date from  text file into array of structures and to export output data to a text file.
It also helps to do more practice with sorting

## Files Required
1. [input_file](https://learn.iiitb.net/pluginfile.php/31238/assignsubmission_file/submission_files/75238/input_file.txt?forcedownload=1)
2. [Structure.c](https://learn.iiitb.net/pluginfile.php/31238/assignsubmission_file/submission_files/75238/structs.c?forcedownload=1)

## Explanation

1. get_struct() function takes file pointer , array of stuct and int n(length of array of struct) as parameters. It takes input from input file and inputs it in each element of array of structures
2. sort() function sort the given array of structures based on id of students in the array.It is sorted using "Bubble sort" --- reads each set of adjacent elements in the string from left to right swapping their positions if they are out of order. 
3. print_struct() function takes file pointer , array of stuct and int n(length of array of struct) as parameters.It prints the structure in the file taken as parameter. Creates file if file does not exist in the same directory.
## Steps to Run files
  1. Install the  files as mentioned above in the same directory
  2. Open terminal 
  3. gcc Structure.c 
  4. ./a.out 
  5. To view ouput_file.txt                 
      - cat ouput_file.txt


## Aryaman Pathak
## IMT2022513
