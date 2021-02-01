# max_end3
CodingBat Python List-1

def max_end3(nums):
  
    answerList = []
  
    for number in nums:
  
      if (nums[0] > nums[-1]) or nums[0] == nums[-1]:
        answerList.append(nums[0])
      else:
        answerList.append(nums[-1])
  
    return answerList
