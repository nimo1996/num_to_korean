# num_to_korean

WieeRd created this function. But threre were several issues.

Mismatch at

1000000176022: 일조영억일십칠만육천이십이

1000000176023: 일조영억일십칠만육천이십삼


i don't know how to tell him, so i edit code and publish here


#Usage

```python
import num2kr

# num = int(input("Integer: "))
num = 12345678
print(num2kr.num2kr(num)) # same as num2kr(num, 0)
print(num2kr.num2kr(num, 1))

# >>> 1234만 5678
# >>> 일천이백삼십사만오천육백칠십팔
```
