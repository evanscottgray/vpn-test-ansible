vpn-test-ansible
===========

ansible deployment for vpn test stuff


#### Services

None Yet

## Using vpn-test-ansible

You'll need to install a few requirements first.

We'll assume that you are in a \*nix environment and have both Python and Pip.

Let's grab a copy of vpn-test-ansible and install the requirements. 

You should do this the context of a virtualenv named `venv`.
```shell
git clone git@github.com:evanscottgray/vpn-test-ansible.git
cd vpn-test-ansible
virtualenv venv
source ./venv/bin/activate
pip install -r requirements.txt
```

Assuming that you have python installed with Homebrew we can start rolling
infrastructure. If you don't have it installed with Homebrew, you might need to
change the python interpreter location in the `development` inventory file.
