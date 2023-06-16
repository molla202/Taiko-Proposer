# Taiko Proposer Kurulum Rehberi
![image](https://user-images.githubusercontent.com/101635385/210137987-bdc3fe6f-270d-40f8-b843-d927a58ca6e9.png)


<h1 align="center"> Taiko Alpha-3 Node Proposer </h1>
</h1>

### Not: dokuman https://github.com/herculessx hercules dokumanıdır. sadece proposer kısmını kopyaladım. kendine emekleri için teşekür ederim. yıldız ve forklamayı arkadaşa yapalım tşkler.
### Taiko Bridge:

 * [Bridge](https://bridge.test.taiko.xyz/#/)
 * [Ağları Cüzdana Ekleme ](https://chainid.network/)
 * [Explorer](https://explorer.test.taiko.xyz/)

 
 ### Linkler
 * [Molla202 Telegram](https://t.me/gokhan_molla)
 * [molla202 Twitter](https://twitter.com/gokhan_molla)
 * [Taiko Dc](https://discord.gg/taikoxyz)
 



## 🟢 Sepolia Ağı TTKO token



Sepolia ağında TTKO test tokenleri geldiyse aşağıdaki işlemleri yapınız.  Gelip gelmediğini kontrol etmek için isterseniz Tilki cüzdanınızdan explorerde görüntüle diyebilir yada tilki cüzdana aşağıdaki sözleşme adresini ekleyerek bakabilirsiniz.

TTKO Sözleşme adresi : 0xE52952B8063d0AE6Bd35E894866d8148976ce645

![image](https://github.com/herculessx/Taiko-Testnet-Node/assets/101635385/1c8eae94-c247-4413-b3f0-40511b1b6416)



```
cd simple-taiko-node
```

```
docker compose down
```



Sözleşme üzerinden deposit işlemi yapın. 50 tane yatırmanız gerekiyor

https://sepolia.etherscan.io/address/0x6375394335f34848b850114b66a49d6f47f2cda8#writeProxyContract#F2

![image](https://github.com/herculessx/Taiko-Testnet-Node/assets/101635385/fc15ef0d-9fa3-4cee-ab58-5279f36b7737)


amount kısmına 5000000000  bunu yazın ve write butonuna basın ardından tilki cüzdanından onay isteyecek. Ardından aşağıdaki işlemlere devam edin.


```
nano .env
```

.env dosyanıza girdiğinizde en altta bulunan alanı aşağıdaki gibi değiştirin. CTRL + X YES komutu ile kaydedin ardından alttaki komut ile nodenizi çaıştırın.


ENABLE_PROPOSER=true <br>
L1_PROPOSER_PRIVATE_KEY=MATEMASK CÜZDAN PRİVATE KEY <br>
L2_SUGGESTED_FEE_RECIPIENT=MATEMASK CÜZDAN ADRESİNİZ <br>



```
docker compose up
```

Sonuç

![image](https://github.com/herculessx/Taiko-Testnet-Node/assets/101635385/6987b0a2-a5d7-4b96-a14e-1806cce648be)


Forklamayı ve beğenmeyi unutmayınız :)
