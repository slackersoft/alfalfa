namespace :sync do
  desc "Sync submodules"
  task :submodules do
    sh "git submodule foreach git pull"
    Dir.chdir ".bash_it" do
      sh "git fetch upstream"
      sh "git rebase upstream/master"
    end
  end
end
