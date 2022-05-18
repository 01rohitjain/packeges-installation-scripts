# packeges-installation-scripts


# Invalid choice: 'eks', maybe you meant:

A possible reason for this is the old version of "kubectl" available in the repository.

 

# Solution:
Install the latest version of "kubectl" using PIP3

sudo yum install -y python3 python3-pip

sudo pip3 install --upgrade --user awscli
 

## To use "kubectl" installed using PIP, you need the PIP binary files directory to be in the PATH variable, to do this:

export PATH=~/.local/bin:$PATH

source ~/.bash_profile
 

In order not to do this every time, you need to add the line:
export PATH=~/.local/bin:$PATH
 
