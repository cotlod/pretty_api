require "bundler/setup"

require "bundler/gem_tasks"
require "rspec/core/rake_task"
require "rubocop/rake_task"
require 'standalone_migrations'

StandaloneMigrations::Tasks.load_tasks

task default: :spec
