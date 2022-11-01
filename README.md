<h1 align="center"> Newrl </h1>

![image](https://user-images.githubusercontent.com/101149671/194660242-7679c111-df7a-49fd-b9eb-1d83cd5e010f.png)

# Selamlar, Newrl chain mainnet rehberi:

 * Ödül hakkında bilgi almak için [buraya](https://newrl.medium.com/join-newrls-incentivized-testnet-and-earn-newrl-tokens-716e6af7b1b9) tıkla. Not: bizim Buray değil.
 * Proje hakkında sorularınız için [buradayım](discord.gg/ruescommunity)
 * Projenin discord kanal [linki](https://discord.gg/GWVZxuH2)

## Sistem gereksinimleri:

 * Net bilgi yok, kendim test ettim:

```
4 CPU
8 RAM
80 GB SSD
```

## Sunucumuzu güncelliyoruz:
```
sudo apt-get update && sudo apt-get upgrade
```

## Git yüklüyoruz
```
git clone https://github.com/git/git
```

## Python3.7+  yüklüyoruz
```
sudo apt update && sudo apt install python3.10-venv
```

## Python3 Pip ve venv yüklüyoruz  
```
sudo apt update
sudo apt install python3-venv python3-pip
```

## Kurulum
```
git clone https://github.com/newrlfoundation/newrl.git
cd newrl
scripts/install.sh mainnet
```

## Cüzdan yedek dönme
auth.json dosyanızı newrl mainnet içine atıyoruz. işlemlere devam ediyoruz. nerde bu auth dosyası testnetini kurduğumuz newrl dosyası içindeki testnet dısyası içinde. böle bulmadınızmı browser üzerinden wallet oluşturmustuk ordan download diyelim sona adını auth.json yapalım ve kurulumu sırasında newrl içindeki mainnet dosyası içine kopyalayalım.

## Düğümü başlatıyoruz
```
apt install screen
```

```
screen -S newrl
```

```
scripts/start.sh mainnet
```

## Node içinde oluşturduğumuz adresi Wallete tanımlama:

 * Aşağıdaki komuttan sonra sırayla:
 * testnet yazıyoruz + enter
 * Y yapıp enterlayıp çıkan çıktıyı kaydedin bu sizin json dosyanızdır.

```
cd newrl
python3 scripts/show_wallet.py
```

![image](https://user-images.githubusercontent.com/101149671/194666768-2920d230-3f2f-4fbe-89ff-84fc222bfb00.png)

