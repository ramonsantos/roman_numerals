# frozen_string_literal: true

require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs.push('lib')
  t.verbose = true
  t.test_files = FileList['test/*_test.rb']
end