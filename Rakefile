
require 'fileutils'
include FileUtils

task :some_name do 
    sh "curl -L -o test-file.jar --fail -H 'Accept: binary/octet-stream' --user '#{ENV['USER']}:#{ENV['PASSWORD']}'  #{ENV['URL']}"
end
