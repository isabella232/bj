require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "vibes-bj"
    gem.summary = %Q{Minor fork of ahoward/bj}
    gem.description = %Q{Forked ahoward/bj because the way the bin/bj before_run method interacts with Main's logger= instance menthod breaks in Ruby 1.8.7}
    gem.email = "josh.warchol@vibes.com"
    gem.homepage = "http://github.com/vibes/bj"
    gem.authors = ["Ara T. Howard", "Joshua Warchol"]
    gem.add_dependency 'main', '>= 2.6.0'
    gem.add_dependency 'systemu', '>= 1.2.0'
    gem.add_dependency 'orderedhash', '>= 0.0.3'
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Bj (or a dependency) not available."
end

