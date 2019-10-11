desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

task :hola do
  puts "hola de Rake!"
end

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
end