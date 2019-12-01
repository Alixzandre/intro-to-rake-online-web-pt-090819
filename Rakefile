desc 'drop into the Pry console'
task :environment do
  require_relative './config/environment'
end
task :console => :environment do
  Pry.start
end
desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end