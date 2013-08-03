require "rubygems"
require 'rake'

desc "Automatically generate site at :4000 for local dev"
task :dev do
  system "jekyll serve --watch --baseurl /"
end # task :dev

desc "Remove _site from directory before committing"
task :clean do
  system "rm -rf _site"
end # task :clean

