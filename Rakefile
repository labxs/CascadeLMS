# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require(File.join(File.dirname(__FILE__), 'config', 'boot'))

include Rake::DSL if defined?(Rake::DSL)
require 'rake'
require 'rake/testtask'
require 'rdoc/task'

require 'tasks/rails'
