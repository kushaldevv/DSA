
Check if a number is Palindrome or Not

```
def isPalindrome(self, x: int) -> bool:

	rev = 0
	
	tmp = x
	
	while x > 0 :
	
		rev = rev * 10 + (x % 10)
		
		x = math.floor(x / 10)

	return rev == tmp
```
