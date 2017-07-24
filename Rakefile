
desc "Run the jekyll development server"
task :serve do |t|
  sh 'bundle exec jekyll serve --config=_config.yml'
end

task :default => :serve

desc "Build the stagin version"
task :staging do |t|
  sh 'bundle exec jekyll build --config=_config.yml,_staging.yml'
end

desc "Build the published version"
task :publish do |t|
  sh 'bundle exec jekyll build --config=_config.yml,_publish.yml'
end
