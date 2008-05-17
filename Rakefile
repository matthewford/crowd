# -*- ruby -*-

require 'rubygems'
require 'hoe'
require './lib/crowd/version'

Hoe.new('crowd', Crowd::Version::STRING) do |p|
  p.rubyforge_name = 'crowd'
  p.author = 'Evgeny Zislis, original: Jason Rimmer & Daniel Morrison'
  p.email = 'evgeny.zislis@gmail.com'
  p.summary = 'Ruby client for Atlassian Crowd'
  p.description = p.paragraphs_of('README.txt', 2..5).join("\n\n")
  p.url = 'http://crowd.rubyforge.org'
  p.changes = p.paragraphs_of('History.txt', 0..1).join("\n\n")
  p.remote_rdoc_dir = ''
  p.extra_deps << ['soap4r']
end

# vim:syn=ruby
