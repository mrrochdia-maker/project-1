# project-1
"Project for Calculating Hours, Minutes, and Seconds"
total_second = input("please type the number of second: \n")
int_total_second = int(total_second)
hours = int_total_second // 3600
minutes = (int_total_second % 3600) // 60
seconds = int_total_second % 60
print("this course is: " + str (hours) + "hours and " + str (minutes) + "minutes long " + str (seconds) + "seconds")
