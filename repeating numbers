#define a function
def find_repeating(arr):
#make a dict count
    num_count = {}
    
 #with the for loop check if the number is already present in the dictionary and if it exist then do nothing if not push it to count 
    for num in arr:
        if num in num_count:
            num_count[num] += 1
        else:
            num_count[num] = 1
            
  #make a empty array then check if the count of the number is greater than one append it to the array repeating_nums
    repeating_nums = []
    for num, count in num_count.items():
        if count > 1:
            repeating_nums.append(num)
    return repeating_nums

#given the array
arr = [1,2,3,6,3,6,1]

print(find_repeating(arr)) #print the repeating numbers
