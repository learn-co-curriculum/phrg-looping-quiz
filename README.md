#Looping Quiz

## Objectives

1. Use the loop keyword
2. Use the break keyword 
3. Use the times keyword
4. Look at a loop and figure out what it will do

???

# Quiz

?: Here is a repeated list of `puts` statements. 

```ruby
puts "hi"
puts "hi"
puts "hi"
puts "hi"
puts "hi"
```

How would you repeat this with loop/break 100 times?

(X)
```ruby
counter = 0

loop do
  puts "hi"
  counter+=1
  break if counter==100
end
``` 
( )
```ruby
loop do
  puts "hi"
  break if counter==100
end
```  
( )
```ruby
loop do
  puts "hi"
end
```  

?: What will this loop do?

```ruby
x=0
while x < 10 do
  puts "so many loops"
end
```

( )puts "so many loops" one time ( )puts "so many loops" 10 times (X)puts "so many loops" infinitely

?: True or False: `puts "Hi"` will never run.

```ruby
10.times do
  break
  puts "Hi"
end
```

(X)true ( )false

???


