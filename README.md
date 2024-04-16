# num_to_korean

WieeRd created this function. But threre were several issues.

https://github.com/WieeRd/KoreanNumber

Mismatch at

1000000000104: 일조억만일백사

1000000000252: 일조억만이백오십이


i don't know how to tell him, so i edited the code and upload here


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
