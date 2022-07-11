# lua-guide

## Printing / commenting 
```
print("Hello Mom!") -- this will print the text hello mom to the console
```

## variables 
```
local x = 5 -- numbers 
local name = "rob" -- strings 
local isThere = true -- boolean 
local aqua = nil -- no value var
```
**Numbers**

operators
- \+ addition
- \- minus
- \* multiply
- / divide
- ^ power
- % modulus

```lua
-- examples
local a = 1
local b = 2
local c = a + b
print(c) -- printss 3 

local d = b - a
print(d) -- prints 1

local x =  1 * 3 * 4 
print(x) -- prints 12

local y = (1+3) * 2
print(y) -- prints 8


print(10/2) -- prints 5
print (2^2) -- prints  4
print(5%2) -- prints 1

print(-b) -- prints -2
```

##Strings
```
local info = "my name is rob and i am "
local age = 18
print(info .. age .. " years old!")
```
