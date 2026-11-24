# SimpleSepet Free

Kendi hostinginize kurduğunuz, ücretsiz e-ticaret yazılımı. PHP 8.2+ ve MySQL 8.0+ / MariaDB 10.6+ ile çalışır.

**[En son sürümü indir (simplesepet-free.zip)](https://github.com/hbasakcioglu-byte/simplesepet-releases/releases/latest/download/simplesepet-free.zip)**

- Tanıtım ve karşılaştırma: https://simplesepet.com
- Canlı demo: https://demo.simplesepet.com
- Kurulum: ZIP içindeki `README.md` ve `docs/INSTALL.md`

Bu depo yalnızca kurulum paketlerini dağıtır. SimpleSepet açık kaynak değildir; Free paketi kendi mağazanızı işletmeniz için ücretsiz kullanım izni verir. Koşullar ZIP içindeki `LICENSE.txt` dosyasındadır.

## Upgrading

**Türkçe.** Yönetim paneli yeni bir sürüm çıktığında üstte bir uyarı gösterir. Yükseltme elle yapılır ve birkaç dakika sürer:

1. **Yedek alın:** veritabanı (hosting panelinden phpMyAdmin → Dışa aktar), `config/local.php` ve `storage/` klasörü.
2. En son `simplesepet-free.zip` dosyasını indirip açın (Pro: zalordigital.com/simplesepet).
3. İçindeki dosyaları hostingdeki mağaza klasörünün üzerine yükleyin ve "üzerine yaz" deyin. **`config/local.php` dosyanız ve `storage/` içindeki yüklemeleriniz korunur**: paket bunları içermez, yalnızca boş klasörleri ve koruma dosyalarını içerir.
4. Mağazanın herhangi bir sayfasını açın: veritabanı kendiliğinden güncellenir. Yönetim panelinde sol menünün altında yeni sürüm numarasını görürsünüz.
5. Bir deneme siparişiyle ödeme ve e-postaları kontrol edin.

Bir sorun olursa dosyaları **ve** veritabanını aynı yedekten birlikte geri yükleyin. Her sürümde neyin değiştiği [Releases](https://github.com/hbasakcioglu-byte/simplesepet-releases/releases) sayfasındadır.

**English.** The admin shows a notice when a new version is out. Updating is manual and takes a few minutes:

1. **Back up** the database (hosting panel → phpMyAdmin → Export), `config/local.php` and the `storage/` folder.
2. Download and unzip the latest `simplesepet-free.zip` (Pro: zalordigital.com/simplesepet).
3. Upload its files over your store folder and choose "overwrite". **Your `config/local.php` and the uploads in `storage/` are kept**: the package contains only empty folders and their protection files.
4. Open any page of the store: the database updates itself. The new version number appears below the admin menu.
5. Check payment and e-mails with a test order.

If something goes wrong, restore the files **and** the database from the same backup. What changed in each version is on the [Releases](https://github.com/hbasakcioglu-byte/simplesepet-releases/releases) page.
