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

### Good

```PowerSgekk error

Get-Process : Cannot find a process with the name "NonExistentProcess". Verify the process name and call the cmdlet again.
At line:1 char:1
+ Get-Process NonExistentProcess
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (NonExistentProcess:String) [Get-Process], ProcessCommandException
    + FullyQualifiedErrorId : NoProcessFoundForGivenName,Microsoft.PowerShell.Commands.GetProcessCommand
```

### Room for improvement
You can click and drag an image into the document - but you should really organise folders for this E.g. 
- Create a new file (assets/newfile) - you need to have a file in the folder to be able to add files to the folder (don't ask!)
- Go to the folder
- Upload the new file
- Delete the placeholder file
![PShellError](https://github.com/WelshieGD/github-docs-example/assets/120795390/4d81724b-f8e8-42ee-8dd9-72480249a133)


## Step 4 - Use Lists

- An itemised list is easier to read
- Honestly, it is

## References
Lets put it all into practice with lists and links
- [Github documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
- [Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)
