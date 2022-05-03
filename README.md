# devops-project-website

## Setup - MacOS

Install Vagrant.
```
brew install vagrant
```

Install virtualbox either from [virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads) or via brew
```
brew install --cask virtualbox
```

> If you get errors when performing `vagrant up`, you may need to install the extension pack. Again, either from the virtualbox downloads page or with brew
>```
>brew install --cask virtualbox-extension-pack
>```

## Usage
Full instructions can be found on [Vagrant's guide here](https://learn.hashicorp.com/collections/vagrant/getting-started).

Initialise your project
```
vagrant init hashicorp/bionic64
vagrant up
```

You can now view the webpage at `http://127.0.0.1:4567`.

When you're done, destroy the VM
```
vagrant destroy
```
