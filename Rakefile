require 'bundler/gem_tasks'
require 'rake/testtask'

TOPLEVEL = File.dirname(__FILE__)
NAME     = File.basename TOPLEVEL
MOFDIR   = "/usr/share/mof/#{NAME}"
CMPIDIR  = "/usr/share/cmpi"
DESTDIR  = ENV['DESTDIR']

task :default => [:test]

Dir['tasks/**/*.rake'].each { |t| load t }
