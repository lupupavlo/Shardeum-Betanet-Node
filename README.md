Guide to Installing Shardeum Betanet Validator

We will install a validator for Shardeum's Betanet network. Don't forget to star and fork from the top right corner. If you have any questions, ask in LossNode Chat.

System Requirements:
NODE TYPE CPU RAM SSD
Betanet 2-4 8 200

To add Sphinx (Betanet) network to metamask, go to: https://docs.shardeum.org/network/endpoints

Important links for Shardeum:
Website
Explorer
Twitter
Discord

Installation of libraries.
sudo apt update && sudo apt upgrade -y
sudo apt-get install curl
sudo apt install docker.io -y
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose

Shardeum Validator installation.
curl -O https://gitlab.com/shardeum/validator/dashboard/-/raw/main/installer.sh && chmod +x installer.sh && ./installer.sh
Answer with 'y', set a password, enter 8080 for the port, and press Enter for the base directory to save it to the .shardeum location.

After seeing an output like the one in the image, proceed.
$HOME/.shardeum/shell.sh
operator-cli gui start

Open any browser on your computer.
Type https://SERVERIP:8080 in the search bar. For example, if your server's IP is 10.11.12.13, type https://10.11.12.13:8080. If it says NOT SECURE, click on ADVANCED and proceed to the site.
Enter the password we set earlier.

Go to the Maintenance section and click Start Node.

Connect Metamask to the SPHINX NETWORK. The instructions for adding the Sphinx network are above.

Get a Faucet from here: Faucet

Stake.

Return to the terminal and enter the following command:
operator-cli start

You can view the status with the following command:
pm2 list

Update 1.1.
Answer 'y' to the questions asked here in order; y, y, your dashboard password, and press Enter for the rest.
curl -O https://gitlab.com/shardeum/validator/dashboard/-/raw/main/installer.sh && chmod +x installer.sh && ./installer.sh

$HOME/.shardeum/shell.sh
operator-cli gui start

If your transaction is not confirmed while staking on the network, you can apply the steps in the following images.

From the Advanced section, click Reset Account and try staking again.

Faucet Links:
https://faucet-sphinx.shardeum.org/
https://chaindrop.org/?chainid=8082&token=0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee
