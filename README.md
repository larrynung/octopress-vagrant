##Quick Script for Running Octopress in Vagrant##

1. [Install Virtual Box](https://www.virtualbox.org/wiki/Downloads)
1. [Install Vagrant](https://docs.vagrantup.com/v2/installation/)
1. Clone Repository 
1. Clone blog reporsity to /home/vagrant/blog
1. `vagrant up`
1. `vagrant ssh`
1. `cd octopress`
1. `rake generate` 
1. `rake preview`

From here, you should be able to go to the browser on your host machine and navigate to http://localhost:4000 and see your Octopress blog running. When you're done, just Ctrl + C out of the webrick task and then the vagrant ssh session -- when you are back to your host machine's terminal, type `vagrant halt`.