nums = [9, 1, 8, 2, 7, 3, 6, 4, 5]

i = 0
while i < len(nums)-1:
    for num in range(len(nums)-1):
        if nums[num] > nums[ num + 1 ]:
            nums[num],nums[ num + 1 ] = nums[ num +1],nums[num]
  
    i += 1 

print(nums)

