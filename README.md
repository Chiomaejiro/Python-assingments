# Python-assingments
this this is to help me do some assignments on python and get the opinions of others to know if I answered them correctly.
#This program determines whether or not 
#three lenghts can form a triangle.
def main():
    
#Get the three lenghts
#Define lenghts as a,b,c
        a=int(input('Enter the lenght of side a:'))
        b=int(input('Enter the lenght of side b:'))
        c=int(input('Enter the lenght of side c:'))
        if c>=a+b:
            print('A triangle can be formed')
        else:
            print('A triangle cannot be formed')
        
 
main()
