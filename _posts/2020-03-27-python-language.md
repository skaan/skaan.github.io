---
title: Python Language
topic: python
---
{::options parse_block_html="true" /}

<div class="card card-body">
## Input / Output
{:.card-title}

```
# Input from STDIN
a = int(input()) # input() returns string
b = int(input())

# Output to console
print(a + b)
```
</div>

<div class="card card-body">
## Arithmetic operations
{:.card-title}

```
# addition
a + b

# subtraction
a - b

# product
a * b

# integer division
a // b

# float division
a / b
```
</div>

<div class="card card-body">
## Branching 
{:.card-title}

```
if <condition>:
    <statement>
```

```
if <condition>:
    <statement>
else:
    <statement>
```

```
if <condition>:
    <statement>
elif <condition>:
    <statement>
else:
    <statement>
```
</div>

<div class="card card-body">
## Looping 
{:.card-title}

```
n = int(input())

for i in range(n):
    <statement>
```
</div>

<div class="card card-body">
## Function definition 
{:.card-title}

```
def aFunction(aParameter):
    print(aParameter)

aFunction("Hello World!")
```
</div>
