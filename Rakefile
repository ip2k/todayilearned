# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "todayilearned"
  gem.executables = ['til']
  gem.homepage = "http://github.com/ip2k/todayilearned"
  gem.license = "Creative Commons by-nc-sa"
  gem.summary = 'TIL is a "Today, I learned..." tool to record things you found interesting and show them to you later'
  gem.description = 'TIL stands for "Today, I learned..." and helps you keep track of things you\'ve learned and stores them in a SQLite file.  It\'ll also reward you for making new entries by showing you things you\'ve learned in the past.'
  gem.email = "github@seanp2k.endjunk.com"
  gem.authors = ["ip2k"]
  # dependencies defined in Gemfile
end
