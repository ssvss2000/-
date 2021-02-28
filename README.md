# -IPO
def greeting
print "Веди своё имя "
name = gets.chomp
print "Веди свою фамилию "
surname = gets.chomp
print "Веди свой возраст "
age = gets.to_i

if age <18
    puts "Привет, #{name} #{surname}. Тебе меньше 18 лет, но начать учится программированию никогда не рано"
 else puts "Привет, #{name} #{surname}. Самое время занятся делом!"
end
end
greeting
