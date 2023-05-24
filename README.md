# PythpnCodeChallenges
1. #Capital indexes
#Write a function named capital_indexes. The function takes a single parameter, 
#which is a string. Your function should return a list of all the indexes in the 
#string that have capital letters.
def capital_indexes(x):
    y = []
    for i in range(len(x)):
        if x[i].isupper():
            y.append(i)
    return y
            
capital_indexes("RoMan MaHat")  # [0, 2, 6, 8]

2. #Middle letter

#Write a function named mid that takes a string as its parameter.
#Your function should extract and return the middle letter. 
# If there is no middle letter, your function should return the empty string.

def mid(x):
    if len(x)%2 == 0:
        return ""
    else:
        return x[(len(x)//2)]
    
mid("Roman") #'m'
