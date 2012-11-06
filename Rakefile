task :default => [:build_shit]

desc "Build the damn thing."
task :build_shit do
  exec "bundle exec compass compile --force --boring"
  exec "bundle exec jekyll"
end