<h1 align="center">Shardeum Betanet Validator Installation

## Validator installation guide for Shardeum's Betanet network. Don't forget to star and fork from the top right. If you have questions: <a href="https://t.me/LossNodeChat" target="_blank" rel="noreferrer noopener" >LossNode Chat English</a>
  
![image](https://user-images.githubusercontent.com/101462877/216376207-8a54c853-8e4c-42bc-b2df-3622c0f2fcd9.png)

## System requirements:
NODE TYPE | CPU     | RAM      | SSD     |
| ------------- | ------------- | ------------- | -------- |
| Betanet | 2-4          | 8         | 200  |
  
  
  
# Adding the Sphinx (Betanet) to metamask: https://docs.shardeum.org/network/endpoints
  
  <img width="1440" alt="Ekran Resmi 2023-02-02 19 47 45" src="https://user-images.githubusercontent.com/101462877/216388297-d9b47afc-c5e6-4245-9bd9-1171a05fa77d.png">

  

## Important links for Shardeum:
- <a href="https://shardeum.org" target="_blank">Website</a>
- <a href="https://explorer-sphinx.shardeum.org" target="_blank">Explorer</a>
- <a href="https://twitter.com/shardeum" target="_blank">Twitter</a>
- <a href="https://discord.gg/shardeum" target="_blank">Discord</a>
  

# 1) Installation of necessary libraries.

```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt-get install curl
```
```
sudo apt install docker.io -y
```

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

# 2) Installing Shardeum Validator.

```
curl -O https://gitlab.com/shardeum/validator/dashboard/-/raw/main/installer.sh && chmod +x installer.sh && ./installer.sh
```

## Enter `y`, `y`, and your dashboard password respectively. After that, just press `Enter` for rest of them.

![image](https://user-images.githubusercontent.com/101462877/219115450-704c2cd5-1d4a-4d3d-9e5d-e9d85bdb858b.png)

# 3) After seeing an output something like the below, continue.

![image](https://user-images.githubusercontent.com/101462877/216381866-e840b39c-1e87-4403-a0d2-32289e206ad4.png)

```
$HOME/.shardeum/shell.sh
```

```
operator-cli gui start
```


# 4) Open a browser on your own computer.

## Write `https://SERVERIP:8080` in the search bar. For example, if your server's IP is 10.11.12.13, type https://10.11.12.13:8080. PRESS IMPROVED IF IT SAYS NOT SAFE, AND FORWARD TO THE SITE.
<img width="578" alt="Ekran Resmi 2023-02-02 19 27 01" src="https://user-images.githubusercontent.com/101462877/216383216-0c28fabd-ba14-41a5-b886-dd87f775911e.png">

## Enter your dashboard password here.

<img width="1440" alt="Ekran Resmi 2023-02-02 19 28 13" src="https://user-images.githubusercontent.com/101462877/216383365-30973dbc-43a5-48cb-a916-6c1a013d4aec.png">
  
 
## Click to `Maintenance`, and click `start node`.
  
<img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://user-images.githubusercontent.com/101462877/216432476-13ee3ec7-9381-4bf2-acb1-09baa8d75ad6.png">

  
## Connect your Metamask on SPHINX NETWORK. How to add Sphinx Network to Metamask?: [Here](https://github.com/thisislexar/Shardeum-Betanet/blob/main/shardeumEng.md#adding-the-sphinx-betanet-to-metamask-httpsdocsshardeumorgnetworkendpoints)
  
  <img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://user-images.githubusercontent.com/101462877/216432965-714c474d-a742-4032-b6ca-bea7972962e1.png">
  
  
## Get test tokens from Faucet. 
  
  ## Faucet Links:

- https://faucet-sphinx.shardeum.org/
- https://chaindrop.org/?chainid=8082&token=0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee
  
  ![image](https://user-images.githubusercontent.com/101462877/216433395-0940fe21-6806-4a62-8d71-8b42330341ff.png)


## Stake your test tokens.
  
  <img width="1440" alt="Ekran Resmi 2023-02-02 22 43 18" src="https://user-images.githubusercontent.com/101462877/216433614-73f58204-608f-419e-9901-7eb80590a577.png">


 ## Get back to your terminal and enter following commands.

```
operator-cli start
```
  

# You can monitor your node/validator with command below.
  

```
pm2 list
```
  
  ![image](https://user-images.githubusercontent.com/101462877/216434539-6bcf7343-fcb3-423a-a7ee-d1cb8f1dde68.png)
  
  
  
## IF YOUR TRANSACTION IS NOT CONFIRMED WHEN STAKE ON THE NETWORK, YOU CAN APPLY THE FOLLOWING IMAGES IN ORDER.

![image](https://user-images.githubusercontent.com/101462877/219121224-08d060db-36d5-4dad-8ca0-56da279e518c.png)

## Reset Account in Advanced settings and try staking again.
![image](https://user-images.githubusercontent.com/101462877/219121371-09e02ef7-8eca-4f0b-ab72-3614043976bf.png)






# For your questions : <a href="https://t.me/LossNodeChat" target="_blank">LossNode Chat English</a>



