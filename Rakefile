require "bundler/gem_tasks"
require "rspec/core/rake_task"

task default: :spec

desc "Run all specs"
RSpec::Core::RakeTask.new do |t|
  t.pattern = "./spec/**/*_spec.rb"
end
