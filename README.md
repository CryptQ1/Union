# Union

Union is the hyper-efficient zero-knowledge infrastructure layer for general message passing, asset transfers, NFTs, and DeFi. It’s based on Consensus Verification and has no dependencies on trusted third parties, oracles, multi-signatures, or MPC. It implements IBC for compatibility with Cosmos chains and connects to EVM chains like Ethereum, Berachain (beacon-kit), Arbitrum, and more.

The upgradability of contracts on other chains, connections, token configurations, and evolution of the protocol will all be controlled by decentralized governance, aligning the priorities of Union with its users, validators, and operators.

# Participate

Join : http://dashboard.union.build

• Connect X , Discord & GitHub
• Connect Wallet
• Do All Missions and Achievements 
• Increase Your Level

Grab Roles On DC : [https://discord.gg/union-build](https://discord.gg/entnqprw)

# Contribute by Participated in Ceremony :

Step 1: https://ceremony.union.build/

Step 2: Choose Linux (windown)/macOS (macbook)

Step 3: on your windown terminal run (admin)

Install docker :

    sudo apt update & sudo apt upgrade -y
    sudo apt install ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev curl git wget make jq build-essential pkg-config lsb-release libssl-dev libreadline-dev libffi-dev gcc screen unzip lz4 -y
    curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
  
    echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
  
    sudo apt-get update
    sudo apt-get install docker-ce docker-ce-cli containerd.io
    docker version
*Run this command if you encounter errors during docker installation*

    sudo groupadd docker
    sudo usermod -aG docker $USER
    newgrp docker
    docker run hello-world
    reboot
    sudo systemctl restart docker

# Set up ceremony

    wsl --install

    mkdir -p ceremony && docker pull ghcr.io/unionlabs/union/mpc-client:v1.2 && docker run -v $(pwd)/ceremony:/ceremony -w /ceremony -p 4919:4919 --rm -it ghcr.io/unionlabs/union/mpc-client:v1.2

Step 4: Return to the browser

Step 5: Click Generate secrets --> Save your secret file

Step 6: Add an address, you may receive rewards for successful contributions. You can enter your union or any cosmos address

*Done !! Waiting for your contribution, mine took 12 weeks*
