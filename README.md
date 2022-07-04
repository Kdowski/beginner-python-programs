# beginner-python-programs
these are a few of the first programs that I have written 

# beer song

import time

word = 'bottles' # assigns the variable word to the value "bottles"

for beer_num in range(99, 0, -1):# sets variable beer_num to a range of
    # numbers 99-0 going down one step every iteration this is a loop
    
    
    print(beer_num, word, "of beer on the wall.")
    time.sleep(1)
    
    print(beer_num, word, "of beer.")
    time.sleep(2)
    
    print("Take one down.")
    time.sleep(1)
    
    print("pass it around.") # prints the lyrics to the song checking that
    # the numaber in the range is greater then one

    time.sleep(2)
    
    if beer_num == 1: # this tells the variable beer_num to stop that loop
        # if the number in the range is 1

        print("no more bottles of beer on the wall.") # the checks that the
        # range is at one and prints the last line in the song

    else: # this says if it is nit the last number in the range then input
        # this new variable

        new_num = beer_num -1 # changes the value of beer_num to beer_num -1
        if new_num == 1:# if the range == 1 change the word bottles to bottle
            word = "bottle" #new value
        print (new_num, word, "of beer on the wall.") # prints the last line
        # as singular

    print() # runs the program

    time.sleep(2)
