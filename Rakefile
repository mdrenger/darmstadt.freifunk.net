require 'html/proofer'

task :build do
  sh "bundle exec jekyll build"
end

task :serve do
  sh "bundle exec jekyll serve"
end

task :test do
  build
  HTML::Proofer.new("./_site",
                    {:href_ignore => [/http(s?):\/\/(.*)\.ffda/]}).run
end

task :clean do
  sh "bundle exec rm -R ./_site"
end

