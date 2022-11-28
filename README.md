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
##  GÜNCELLEME  her sürümde aynıdır
```
screen -X -S newrl kill
```
```
screen -S newrl
```
```
cd newrl
```
```
scripts/install.sh mainnet
```
```
scripts/start.sh mainnet
```

## Portları açalım önce
```
sudo ufw status
```
```
sudo ufw allow 22
sudo ufw allow 22/tcp
sudo ufw allow 21
sudo ufw allow 21/tcp
sudo ufw allow 8456
sudo ufw allow 8456/tcp
```
```
sudo ufw enable
```



## Sunucumuzu güncelliyoruz:
```
sudo apt-get update && sudo apt-get upgrade
```

## Git yüklüyoruz ( yuklemesse hata verirse  ( apt install git ) yazıyoruz sona bunu yazıyoruz
```
git clone https://github.com/git/git
```

## Python3.7+  yüklüyoruz
```
sudo apt update && sudo apt install python3.10-venv
```
Not: Burda hata alırsanız önemsemeyin devam
## Python3 Pip ve venv yüklüyoruz  
```
sudo apt update
sudo apt install python3-venv python3-pip
```

## Daha önce testnet kuruluysa

```
cd newrl
```
```
screen -X -S newrl kill
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

## Node içinde oluşturduğumuz adresi Wallete tanımlama:  UNUTMAYIN LOGLAR AKMAYA BASLADIĞINDA BU SCREENDEN CTRL A D İLE ÇIKIP DEVAM EDİYORUZ. TEKRAR GİRMEK İSTERSENİZ : screen -a -r newrl  ( yine çıkarken ctrl ad )

 * Aşağıdaki komuttan sonra sırayla:
 * mainnet yazıyoruz + enter
 * Y yapıp enterlayıp çıkan çıktıyı kaydedin bu sizin json dosyanızdır.

```
cd newrl
python3 scripts/show_wallet.py
```

Çıkan çıktı yedek aldığımız ve döndüğümüz dosyanın içindeki adresle aynıysa doğru yapmışız demektir.

![image](https://user-images.githubusercontent.com/101149671/194666768-2920d230-3f2f-4fbe-89ff-84fc222bfb00.png)


## https://www.newrlscan.io/  sitesinden ipnizi kontrol edin bir kaç saat sona buraya düşmesi lazım nodun

## şimdi mainneti kurduk ipmiz görunuyor. gelelim birbirimize trust puanı vermeye.cüzdanınızı bana tg özelden atınız isteyenler

## Cüzdanlar
```
0x2de4136d410cab684cb17d3c5f7868ee50b55101
```
```
0xda5e0c374244f8701ead84a5b49d24c24e9a0ee8
```
```
0xbd5df0304fcd62b8cb0883ab45487c34d55957f4
```
```
0xffb9055c8ad06a87c69bc4f11f41f531064bd27b
```
```
0x54b60f681f367498a16800700632d40ea5b82946
```
```
0x4adfa4ffedf180c9e3343ce016e3404310c059cd
```
```
0xb9f5e3f18d65b601a238fb457eadb6697a6a2cb1
```
```
0xbbc746f991bb1e6ab951aa7f61f52ae3cded682c
```
```
0xaaeaa756d5bc80749b0526c3a5194da8d54a0f73
```
```
0x901d54843ab9f6bc9de5f5ce886a3a732030455c
```
```
0x9b2d184ee616ffdb3a8a7e5d82e3bc07de1b8985
```
```
0x279657578d3178a8cdcbd8921015b1ab7ec80cb4
```
```
0x2cc2dcba84b9687bebe7a26bccecf2119eb17528
```
```
0xfd7537afe2e026a3544844b059e9de5b361687e5
```
```
0x1849a0178c63b55fa7f8709abaa1de1a6e47c93e
```
```
0x413a470865ce992d6d07791932dfa07296393ec3
```
```
0x1849a0178c63b55fa7f8709abaa1de1a6e47c93e
```
```
0x698a446b54be28caf934aa82d6e1baf88f0ba990
```
```
0x7775d1b6b37f96e1d3f987d4d9192892f7689eca
```
```
0x873779fe686fc61e7ee9175eca7170a496680669
```
```
0x95f93b2ab8db52c233e3bb31ecab6539280d6277
```
```
0xa6aa4395e3bb1fe50c49ea708ec58b01856d294e
```
```
0xfd5672c2a087bb1955de34f3f4a89672a4c77e2d
```
```
0xddfc19a4f2d4b3442e41221b05aa2e3f6e746436
```
```
0x05879ae7eae1d5192dffc4c402d968071e9686cf
```
```
0x7dd2d78cb46c8852ad96bf7e22e52fd209e680fd
```
```
0xfaca960ae340fb2c649ffb8e1cacc340bba66abf
```
```
0x4895c017eeed0ad3969a52dd8975d0ff6aea38c0
```
```
0xb70285b7a729ee576b1aa1f6dd04abc78e312436
```
```
0xf11ed0d86a8c9e6f47f2f97adc1218b3d2d58d30
```
```
0x6fb3c1d9a7d5110e4c33b29df2c6f721651f77a5
```
```
0xbb10402baeb5339f6df053437ad0ac34a0322d1e
```
```
0x18d4fedce6525211ac6613e3eb14ec11ea57b48c
```
```
0x4ecbeb869d6445b36323573446ccd3a09c7eb90a
```
```
0x27022715377f4f278fede658b67b8e7c9eff16b4
```
```
0x3f79e4921b6414417b9fedd38b980f34cb2600a5
```
```
0xf12f348440c680e196527709c70dce1516de4ace
```
```
0x1b4c994ee71479f49225cedc4cf61118b535e376
```
```
0xed2dbf69ee4cf612cc53e2a3a503e52569052ffc
```
```
0xf12f348440c680e196527709c70dce1516de4ace
```
```
0x900e4b8ca20d97b0e760fdcdeede1188c3054c11
```
```
0xf49af24a979b8f2c0cd20e37ca155eb1927365d1
```
```
0x9d50dd28694198c187b6601cf962ea56c1e9c8d1
```
```
0xf55b92210de9d80a6b5513cfb6508af4f97b79bc
```
```
0x8530d44b9abed87cc5e049a170705d1dabdd0e0e
```
```
0xf9ffc4cce52c237fbdfec2cf6557d63b9df382e6
```
```
0x2f73f7c45767921fa986ffd5016628b34c2c1709
```
```
0x25b082defd56363cef9f87e7ed1826fdd98326c1
```

![1](https://user-images.githubusercontent.com/91562185/199553273-3859ecc1-b040-447e-8acb-d14f9aa867ce.jpg)

![2](https://user-images.githubusercontent.com/91562185/199553329-3ec31a41-e110-42ef-88a6-9629e506020e.jpg)



