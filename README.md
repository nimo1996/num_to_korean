# num_to_korean
change int num to Korean

WieeRd created this function. But threre were several issues.

Mismatch at 1000000176022: 일조영억일십칠만육천이십이 -> 1000100176022
Mismatch at 1000000176023: 일조영억일십칠만육천이십삼 -> 1000100176023
Mismatch at 1000000176024: 일조영억일십칠만육천이십사 -> 1000100176024
Mismatch at 1000000176025: 일조영억일십칠만육천이십오 -> 1000100176025
Mismatch at 1000000176026: 일조영억일십칠만육천이십육 -> 1000100176026
Mismatch at 1000000176027: 일조영억일십칠만육천이십칠 -> 1000100176027
Mismatch at 1000000176028: 일조영억일십칠만육천이십팔 -> 1000100176028
Mismatch at 1000000176029: 일조영억일십칠만육천이십구 -> 1000100176029
Mismatch at 1000000176030: 일조영억일십칠만육천삼십 -> 1000100176030

i don't know how to tell him, so i edit code and publish here


#Usage

import num2kr

# num = int(input("Integer: "))
num = 12345678
print(num2kr.num2kr(num)) # same as num2kr(num, 0)
print(num2kr.num2kr(num, 1))

# >>> 1234만 5678
# >>> 일천이백삼십사만오천육백칠십팔
