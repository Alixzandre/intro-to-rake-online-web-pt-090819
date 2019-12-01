desc 'drop into the Pry console'
task :environment do
  require_relative './config/environment'
end
task :console => :environment do
  Pry.start
end