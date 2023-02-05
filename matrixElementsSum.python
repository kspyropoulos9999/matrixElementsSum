# program assumes that all submatrices are of equal length

def solution(matrix):
    
    arr = []
    subCounter = 0
    elementCounter = 0 
    
    # iterate through matrix and count submatrix quantity
    for submatrix in matrix:
        subCounter += 1
        
        # get elements in submatrix appended to arr array
        for element in submatrix:
            arr.append(element)
            
    # count elements in a submatrix 
    for element in submatrix:
        elementCounter+=1
        
    counter = 0
    array = []
    
    # for loop recognizes the pattern that every element below element equaling zero, must have no occupants and therefore must be equal to zero
    for i in range(len(arr)-1): 
        if arr[i] == 0 and i < (len(arr)-elementCounter):
            arr[i+elementCounter] = 0
    
    sum = 0 
    
    # calculate sum of all occupants
    for i in arr:
        sum += i
    return sum
