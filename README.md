# missing_number
This python program finds missing numbers in a given list
def missing_numbers(num_list):
      original_list = [x for x in range(num_list[0], num_list[-1] + 1)]
      num_list = set(num_list)
      return (list(num_list ^ set(original_list)))
      if True:
      	  return (list(num_list ^ set(original_list)))
      else:
      	print("list is complete")

print(missing_numbers([1,2,3,4,6,7,10]))
print(missing_numbers([8,9,10]))
