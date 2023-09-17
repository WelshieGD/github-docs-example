# Writing Good Documentation.

## Step 1 - Using Codeblocks.


Codeblocks in markdown make it *very easy* for tech people to **copy, paste and share** code. 
chat.
```ruby
class Person
  attr_accessor :name, :age

  def initialize(name, age)
    @name = name
    @age = age
  end

  def introduce
    puts "Hi, my name is #{@name} and I am #{@age} years old."
  end
end

# Create an instance of Person
person = Person.new("John Doe", 30)

# Access and modify attributes
person.name = "Jane Doe"
person.age = 35

# Call the introduce method
person.introduce
```

## Step 2 - Reference Links and recognise the original developer \ author
I learnt Github markdown from [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)

## Step 3 - Include errors. Try to avoid screenshots as it isn't possible to copy code from a screenshot!

```PowerSgekk error

Get-Process : Cannot find a process with the name "NonExistentProcess". Verify the process name and call the cmdlet again.
At line:1 char:1
+ Get-Process NonExistentProcess
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (NonExistentProcess:String) [Get-Process], ProcessCommandException
    + FullyQualifiedErrorId : NoProcessFoundForGivenName,Microsoft.PowerShell.Commands.GetProcessCommand
```
