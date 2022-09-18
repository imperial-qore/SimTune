# SimTune

This is the code repository that supplements the work: "SimTune: Simulator Tuning to Bridge the Reality Gap for Resource Management in Edge Computing".

<a href="https://gitpod.io/#https://github.com/imperial-qore/SimTune/">
    <img src="https://gitpod.io/button/open-in-gitpod.svg" alt="Open in gitpod">
  </a>


## Quick Start Guide

### Installation.

```console
# install prerequisites
sudo apt -y update && sudo apt install -y rsync python3-pip
pip3 install --upgrade pip
pip3 install matplotlib scikit-learn
pip3 install -r requirements.txt
export PATH=$PATH:~/.local/bin
sudo chmod 400 keys/id_rsa

# install Azure CLI
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
```

Or use pre-installed gitpod.

### Quick test.

```console
python3 simtune.py
```

## License

BSD-3-Clause. 
Copyright (c) 2022, Shreshth Tuli.
All rights reserved.

See License file for more details.
