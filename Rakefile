begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "cucumber-rails"
    gemspec.summary = "Cucumber Generators and Runtime for Rails"
    gemspec.description = "Cucumber Generators and Runtime for Rails"
    gemspec.email = "cukes@googlegroups.com"
    gemspec.homepage = "http://cukes.info"
    gemspec.authors = ["Dennis Blöte", "Aslak Hellesøy"]
    gemspec.homepage = "http://github.com/dbloete/cucumber-rails"
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install jeweler"
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }