# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile for trainer project
# 2014 Carlos Pintado <carlosmpintado@gmail.com>


# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

# Beginning of main configuration section
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  # Beginning of vm "repo" configuration section
  config.vm.define "repo" do |repovm|
    repovm.vm.box      = "centos6.4"
    repovm.vm.hostname = "repo" 
  end
  # End of vm "repo" configuration section

  # Beginning of vm "test" configuration section
  config.vm.define "test" do |testvm|
    testvm.vm.box = "centos6.4" 
    testvm.vm.hostname = "test" 
  end
  # End of vm "repo" configuration section

end
# end of main configuration section
