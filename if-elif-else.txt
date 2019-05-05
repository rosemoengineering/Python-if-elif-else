# how to use if - elif - else commands in Python

num=int(input("Please, Write an integer number....\n"))

if num>=0 and num<10 :
# if the num is bigger than or equal to zero, and num is smaller than 10,
# type to screen, " The number which is written, is smaller than 10. "
    print(" The number which is written, is smaller than 10. ")
elif num<0 :
# if the num is smaller than zero,
# type to screen, " The number which is written, is negative. "
# and also type to screen " Please, write a positive integer number. "
    print(" The number which is written, is negative. ")
    print(" Please, write a positive integer number. ")
else :
#if the num is bigger than 10,
#type to screen, " The number which is written, is not smaller than 10. "
    print(" The number which is written, is not smaller than 10. ")
        
