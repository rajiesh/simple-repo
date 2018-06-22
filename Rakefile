
require 'fileutils'
include FileUtils

task :dummy do 
    sh "curl -L -o test-file.jar --fail -H 'Accept: binary/octet-stream' --user '#{ENV['USER']}:#{ENV['PASSWORD']}'  #{ENV['URL']}"
end
