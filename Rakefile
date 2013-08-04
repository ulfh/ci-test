
task :default => [:build]

desc "Build"
task :build do
    sh "xctool -workspace covtest.xcodeproj/project.xcworkspace -scheme covtest ONLY_ACTIVE_ARCH=NO build"
end
