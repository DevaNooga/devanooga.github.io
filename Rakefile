# frozen_string_literal: true

# Based on http://stackoverflow.com/a/9017437

require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs << 'test'
  t.test_files = FileList['test/*_test.rb']
  t.verbose = true
end
