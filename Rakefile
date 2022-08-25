# require_relative './config/environment'
# require 'sinatra/activerecord/rake'

# CREATE TASK WITHOUT DESCRIPTION
task :hello do 
    puts "Hello mate!"
end
# CREATE TASK WITH DESCRIPTION
task :complex_math do 
    output = (0.01/100*14000000)
    puts output
end
# ORGANIZE TASKS IN NAMESPACES
namespace:math_concepts do
    desc "find addition"
    task :add do
        puts "addition"
    end

    desc "find subtraction"
    task :sub do
        puts "subtraction"
    end
end