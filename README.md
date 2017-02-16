# bucky
This project is about counting the number of times a word appears in a sentence. 

#This Progra is written and python 2.7.13

#Accepts the name of the file from the user...
fileName = raw_input("Please enter name of the file: ")

#Using a try and except statement to open the file..
try:
    fhand = open(fileName)
    count = {}
    for eachLIne in fhand:
        wordList = eachLine.split()
        for eachWord in wordLIst:
            if eachWord not in count:
                count[eachWord] = 1
            else:
                count[eachWord] += 1
     print count
     
except:
    print "The file you provided does not exits."
                
