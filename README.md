<h1 align="center">Shardeum Betanet Validator Kurulum Rehberi

## Shardeum'un Betanet ağında validator kuruyoruz. Sağ üstten yıldızlayıp forklamayı unutmayalım. Sorularınız olursa: [LossNode Chat](https://t.me/LossNode)

![image](https://user-images.githubusercontent.com/101462877/216376207-8a54c853-8e4c-42bc-b2df-3622c0f2fcd9.png)

## Sistem gereksinimleri:
NODE TİPİ | CPU     | RAM      | SSD     |
| ------------- | ------------- | ------------- | -------- |
| Testnet | 2-4          | 8         | 100  |
  
  

## Shardeum için önemli linkler:
- [Website](https://shardeum.org)
- [Twitter](https://twitter.com/shardeum)
- [Discord](https://discord.gg/shardeum)


# 1) Kütüphanelerin kurulumu.

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

# 2) Shardeum Validator kurulumu.

```
curl -O https://gitlab.com/shardeum/validator/dashboard/-/raw/main/installer.sh && chmod +x installer.sh && ./installer.sh
```

## Sırasıyla `y` diyin, bir şifre belirleyin, port sorduğunda `8080` girin, base directory sorduğunda direkt `Enter` basın ki .shardeum konumuna kaydetsin.

<img width="1440" alt="Ekran Resmi 2023-02-02 19 12 16" src="https://user-images.githubusercontent.com/101462877/216379061-943482d3-1f8e-4d11-9241-8a39be09065b.png">

<img width="1440" alt="Ekran Resmi 2023-02-02 19 13 12" src="https://user-images.githubusercontent.com/101462877/216379370-a8568c65-85ca-477a-a8e1-2a4e3f2c424f.png">

![image](https://user-images.githubusercontent.com/101462877/216380082-8c616ccd-8f60-4ec4-9324-ff1097c20eba.png)

# 3) Aşağıdaki görseldeki gibi bir çıktı gördükten sonra devam ediyoruz.

![image](https://user-images.githubusercontent.com/101462877/216381866-e840b39c-1e87-4403-a0d2-32289e206ad4.png)

```
$HOME/.shardeum/shell.sh
```

```
operator-cli gui start
```


# 4) Bilgisayarımızda herhangi bir tarayıcıyı açıyoruz.

## Arama çubuğuna `https://SUNUCUIP:8080` şeklinde yazıyoruz. Örneğin, sunucunuzun IP'si 10.11.12.13 ise https://10.11.12.13:8080 yazıyoruz. GÜVENLİ DEĞİL DERSE GELİŞMİŞ, SİTEYE İLERLE DİYORUZ.

<img width="578" alt="Ekran Resmi 2023-02-02 19 27 01" src="https://user-images.githubusercontent.com/101462877/216383216-0c28fabd-ba14-41a5-b886-dd87f775911e.png">

## Yukarıda belirlemiş olduğumuz şifreyi giriyoruz.

<img width="1440" alt="Ekran Resmi 2023-02-02 19 28 13" src="https://user-images.githubusercontent.com/101462877/216383365-30973dbc-43a5-48cb-a916-6c1a013d4aec.png">


DEVAM EDECEĞİM....


# Sorularınız olursa: [LossNode Chat](https://t.me/LossNode)



