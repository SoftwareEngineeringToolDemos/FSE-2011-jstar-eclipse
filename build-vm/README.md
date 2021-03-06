This document specifies the instructions for creating an Ubuntu 14.04 LTS Virtual Machine that allows you to run the tool jStar-Eclipse.<br/>

<b>Steps:</b>

* Download & Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).<br/>
* Download & Install [Vagrant](https://www.vagrantup.com/downloads.html).<br/>
* Create a new directory and place this [VagrantFile](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-jstar-eclipse/blob/master/build-vm/Vagrantfile) and [bootstrap1.sh](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-jstar-eclipse/blob/master/build-vm/bootstrap1.sh), [bootstrap2.sh](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-jstar-eclipse/blob/master/build-vm/bootstrap2.sh), [bootstrap3.sh](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-jstar-eclipse/blob/master/build-vm/bootstrap3.sh) and [bootstrap4.sh](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-jstar-eclipse/blob/master/build-vm/bootstrap4.sh) files in it.<br/>
* Navigate to this directory from command prompt/terminal.<br/>
* Run the command "vagrant plugin install vagrant-reload" on the command prompt/terminal.<br/>
  * This will install the plugin to reload the Virtual Machine after specific intervals.<br/>
* Once the plugin is installed, run the command "vagrant up" on the command prompt/terminal.<br/>
* The Virtual Machine won't require you to login. But in case it goes to sleep, enter "vagrant" as the username as well as password.<br/>

<b>References:</b>

* https://docs.vagrantup.com/v2/getting-started/index.html
* http://thediscoblog.com/blog/2013/11/18/provisioning-ubuntu-with-java-in-3-steps/
* https://github.com/abstools/abstools/blob/master/Vagrantfile
* https://gist.github.com/scottvrosenthal/11187116
* http://stackoverflow.com/questions/10268583/downloading-java-jdk-on-linux-via-wget-is-shown-license-page-instead
* http://askubuntu.com/questions/80013/how-to-pin-eclipse-to-the-unity-launcher
