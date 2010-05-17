require 'rubygems'
require 'rake'

begin

  require 'jeweler'

  Jeweler::Tasks.new do |gem|
    gem.name        = 'dm-do-adapter'
    gem.summary     = 'DataObjects Adapter for DataMapper'
    gem.description = gem.summary
    gem.authors     = ["Dan Kubb"]
    gem.email       = %q{dan.kubb@gmail.com}
    gem.homepage    = 'http://github.com/datamapper/dm-do-adapter'

    gem.add_dependency 'data_objects',      '~> 0.10.1'
    gem.add_dependency 'dm-core',           '~> 0.10.3'

    gem.add_development_dependency 'rspec', '~> 1.3'
  end

  Jeweler::GemcutterTasks.new

  FileList['tasks/**/*.rake'].each { |task| import task }
rescue LoadError
  puts 'Jeweler (or a dependency) not available. Install it with: gem install jeweler'
end
