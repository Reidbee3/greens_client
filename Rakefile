require "bundler/gem_tasks"
require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new('spec')

task :console do
  require 'irb'
  require 'irb/completion'
  require './lib/greens_client'
  ARGV.clear
  IRB.start
end
task :c => :console

task :default => :spec