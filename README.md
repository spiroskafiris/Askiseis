# Askiseis
Askisi 1

punctuations = "!"

my_str = "Hello!!! he said and went"

no_punct = ""
for char in my_str:
   if char not in punctuations:
       no_punct = no_punct + char 

print(no_punct+"!")
__________________________________________________________________________

Askisi 3

def move_zero(num_list):
    a = [0 for i in range(num_list.count(0))]
    x = [ i for i in num_list if i != 0]
    x.extend(a)
    return(x)

print("give me some numbers separated with space please")
b = [int(x) for x in input().split()]
print(move_zero(b))
_______________________________________________________________________________

Askisi 5

def Harshad(num):
    num_string = str(num)
    num_list = list(num_string)
    num_int_list = []
    num_sum = 0
    for x in num_list:
        num_sum += int(x)
    num_result = num/num_sum
    if num_result == round(num_result):
        return True
    else:
        return False

harshad_numbers = []

for num in range(1,1001):
    if Harshad(num) == True:
        harshad_numbers.append(num)

print(harshad_numbers)

____________________________________________________________________________________-
Οσες φορες προσπαθησα να τις ανεβασω κανονικα μου εμφανισε το μηνυμα "something went really wrong...".
Μετα απο πολυ προσπαθεια κατεληξα να τις ανεβασω ετσι δεν βρηκα λυση.
