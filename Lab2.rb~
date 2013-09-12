# Part1: Hello World
puts "===Problem 1==="
class HelloWorldClass
    def initialize(name)
       @name = name.capitalize
    end
    def sayHi
        puts "Hello #{@name}!"
    end
end
hello = HelloWorldClass.new("guo hui tan")
hello.sayHi

# Part2: Strings
puts "===Problem 2a==="
def palindrome?(string)
	string = string.downcase.gsub(/\W/, '')
	string == string.reverse
end

puts palindrome?("A man, a plan, a canal -- Panama")  
puts palindrome?("Madam, I'm Adam!")
puts palindrome?("Abracadabra")
puts palindrome?("racecar") 

puts "===Problem 2b==="
def count_words(string)
	Hash[string.downcase.split(/\W+/).group_by{|string| string}.map{|s| [s[0], s[1].size]}]
end

puts count_words("A man, a plan, a canal -- Panama")
    # => {'a' => 3, 'man' => 1, 'canal' => 1, 'panama' => 1, 'plan' => 1}
puts count_words ("Doo bee doo bee doo")
    # => {'doo' => 3, 'bee' => 2}


