task :migrate do
  require 'models.rb'
  DataMapper.auto_migrate!
end

task :populate do
  require 'fixtures.rb'
  20.of {Album.gen}
end