<div class="content pb-4">
    
<section class="my-3" id="section-intro">

# Giriş

**smmbooster**, Laravel kullanılarak oluşturulmuş çevrimiçi bir sosyal medya pazarlama aracıdır. Bu uygulama, Sosyal Medya Pazarlama Hizmetlerinizi satmanıza veya api sağlayıcıları aracılığıyla diğer SMM panel hizmetlerini yeniden satmanıza olanak tanır. Müşterilerinize Facebook beğenileri, Instagram takipçileri, Twitter takipçileri, Youtube izleyicileri, web sitesi trafiği ve daha fazlası gibi tüm paketleri veya hizmetleri sunabilirler. Paneliniz tamamen dinamiktir ve sosyal medya hesaplarınız için veya SMM hizmetleri bayisi olarak kullanılabilir. Bu sizin sosyal medya hesaplarınız için mi yoksa bir SMM hizmetleri bayisi misiniz? İhtiyacınıza uygun birçok hizmeti ve paketi oluşturabilirsiniz.
<div>
   :heart: Eğer bu betiği beğenirseniz lütfen bana bir yıldız ⭐ vererek daha fazla özellik eklememe teşvik edin
 </div>

</section>
    
<sction>

# Demo

<div>
  🔗   <a href="https://smmbooster.mediarayek.com" target="_blank"> DEMO VERSİYONUNA GİT</a>
</div>
    ------------------------------------
<ul>
     <li><strong>Admin : </strong></li>
       <div>
           E-posta : <strong>admin@admin.com</strong><br>
           Şifre : <strong>admin123</strong> <br>
           Bağlantı : <strong><a href="https://smmbooster.mediarayek.com/admin/login" target="_blank">admin kontrol paneli</a></strong>
       </div>
       <li><strong>Kullanıcı : </strong></li>
       <div>
           E-posta : <strong>user@user.com</strong><br>
           Şifre : <strong>user123</strong><br>
           Bağlantı : <strong><a href="https://smmbooster.mediarayek.com/login" target="_blank">kullanıcı kontrol paneli</a></strong>
       </div>
 </ul>
</section>


<section class="my-3" id="section-requirements">

# Gereksinimler

**smmbooster** betiği Laravel 8 ile oluşturulmuştur. Laravel çerçevesinin 8 sürümü için aşağıdaki PHP sürümü ve uzantılara sahip olduğunuzdan emin olmalısınız

<table class="table mb-3 table-bordered table-hover table-vcenter">

<tbody>

<tr>

<td>Sunucu</td>

<td>Apache/Nginx</td>

</tr>

<tr>

<td>PHP sürümü</td>

<td>PHP sürümü >= 7.3</td>

</tr>

<tr>

<td>allow_url_fopen</td>

<td>`allow_url_fopen=On` (php.ini dosyası)</td>

</tr>

<tr>

<td>PHP cURL</td>

<td>Gerekli. (Curl Kütüphanesi, Curl_init Fonksiyonu ve Curl_exec)</td>

</tr>

<tr>

<td>PHP OpenSSL</td>

<td>Gerekli. (Güvenli veri şifrelemesi için.)</td>

</tr>

<tr>

<td>PHP PDO</td>

<td>Gerekli. (MySQL sunucusuna güvenli bağlantı oluşturmak için)</td>

</tr>

<tr>

<td>Zip</td>

<td>PHP zip uzantısı gereklidir (güncelleme, kurulum vb. için)</td>

</tr>

<tr>

<td>PHP CURL</td>

<td>PHP CURL uzantısı gereklidir</td>

</tr>

<tr>

<td>Mod Rewrite Etkin</td>

<td>Gerekli</td>

</tr>

<tr>

<td>Mbstring PHP Uzantısı</td>

<td>Gerekli</td>

</tr>

<tr>

<td>XML PHP Uzantısı</td>

<td>Gerekli</td>

</tr>

<tr>

<td>Tokenizer PHP Uzantısı</td>

<td>Gerekli</td>

</tr>

<tr>

<td>JSON PHP Uzantısı</td>

<td>Gerekli</td>

</tr>

<tr>

<td>Ctype PHP Uzantısı</td>

<td>Gerekli</td>

</tr>

<tr>

<td>BCMath PHP Uzantısı</td>

<td>Gerekli</td>

</tr>

<tr>

<td>Fileinfo PHP Uzantısı</td>

<td>Gerekli</td>

</tr>

</tbody>

</table>

</section>

<section class="my-3" id="section-install">

# Nasıl Kurulur

Betik kurulumu için aşağıdaki kılavuzu takip edin:
<div class="font-weight-bold">Adım 1 - depoyu yerel makineye klonlayın.</div>
    <pre>git clone https://github.com/mediarayek-me/smmbooster.git</pre>

<div class="font-weight-bold">Adım 2 - projeniz dizininde çalıştırın.</div>
    <pre>composer install && npm install</pre>
    <div>  vendor ve node_modules dizinlerini oluşturmak için </div> <br>
    
  
<div class="font-weight-bold">Adım 3 - betiği yerel makinenizde test etmek için sadece çalıştırın.</div>
    <pre>php artisan serve</pre>
    <br> <br>
   <div class="font-weight-bold">Adım 4 - yeni bir veritabanı oluşturun.</div>
 <div class="font-weight-bold">Adım 5 - Tüm istenen bilgileri doldurun ve Tamam'a tıklayın</div>
    
    
  <h3>canlı sunucunuzda test etmek için</h3>
<div class="font-weight-bold">Adım 0 - hosting hesabınızda yeni bir veritabanı oluşturun.</div>

<div class="font-weight-bold">Adım 1 - tüm proje dosyalarını web hostinginize yükleyin. </div>

<div class="font-weight-bold">Adım 2 - Tarayıcınızı açın ve kurulum sayfasına gidin. (Bu durumda `www.domain.com` ) </div>

<div class="font-weight-bold">Adım 3 - Tüm istenen bilgileri doldurun.</div>
Yönlendirildikten sonra, tüm istenen bilgileri doldurmanız gerekecek (veritabanı adı, veritabanı şifresi... vb.)
<div class="font-weight-bold">Adım 4 - Kurulumu Tamamla.</div>
3\. adımdaki tüm istenen bilgileri doldurduktan sonra Tamam'a tıklayın. Her şey yolundaysa birkaç saniye sonra başarıyla mesajını göreceksiniz.
 <div class="font-weight-bold">Adım 5 -  keyfini çıkarın 😃 .</div>

</section>

<section id="section-category">

# Kategori Ekle

Yönetici Paneli tamamen dinamiktir, bu nedenle kategorileri ekleyip/güncelleyebilirsiniz.

1.  Yönetici olarak giriş yapın, Kategorilere gidin
2.  Yeni ekle'ye tıklayın.
3.  Kategori Adı, açıklama ve Varsayılan olarak etkin durum seçin, sıra numarasını seçin vb.
4.  Kategoriyi devre dışı bırakmak istediğinizde, durumu devre dışı yapın.
5.  Kaydet'e tıklayın

</section>

<section id="section-service">

# Hizmet Ekle

Yönetici Paneli tamamen dinamiktir, bu nedenle hizmetleri ekleyip/güncelleyebilirsiniz.

1.  Yönetici olarak giriş yapın, Hizmetlere gidin
2.  Yeni ekle'ye tıklayın.
3.  Hizmet türünü api veya normal olarak seçin.
4.  Hizmet Adı, açıklama ve Varsayılan olarak etkin durum seçin vb.
5.  Tek ürün başına fiyat. Örn: 1 Beğeni için fiyat = 0.01 vb.
6.  Minimum miktar - Örn: 100.
7.  Maksimum miktar - Örn: 3000.
8.  Hizmeti devre dışı bırakmak istediğinizde, durumu devre dışı yapın.
9.  Kaydet'e tıklayın

</section>

<section id="section-order">

# Sipariş Ekle

Herhangi bir Kullanıcı yeni sipariş verebilir.

1.  Yönetici olarak giriş yapın, Siparişlere gidin
2.  Sipariş kategorisi seçin.
3.  Bir hizmet seçin.
4.  Geçerli bir bağlantı ekleyin.
5.  Miktar ekleyin.
6.  Kaydet'e tıklayın

</section>

<section id="section-api">

# Yeni API Sağlayıcı Ekle

Herhangi bir Yönetici yeni API sağlayabilir.

1.  Yönetici olarak giriş yapın, API sağlayıcılara gidin
2.  ad ve URL ekleyin .
3.  api sağlayıcı tarafından sağlanan Api anahtarını ekleyin.
4.  Hizmeti devre dışı bırakmak istediğinizde, durumu devre dışı yapın.
5.  Kaydet'e tıklayın
6.  Api'nin bağlandığını ve api'nin otomatik olarak tüm hizmet ve kategorileri çekeceğini göreceksiniz

betik, birçok smm paneli ile uyumludur, eğer hizmetleri yeniden satmak istiyorsanız.

*   [MOMO panel](https://momopanel.com/)
*   [VINA SMM](https://vinasmm.com/)
*   [HQ SmartPanel](https://hqsmartpanel.com/)

</section>

<section id="section-settings">

# Ayarları Düzenle

Yöneticinin ihtiyacına göre birçok ayarı değiştirebileceği ayarlar bulunmaktadır.

1.  Genel Ayarlar: genel ayarları düzenlemek için.
2.  Hizmet Ayarları: hizmet ayarlarını düzenlemek için.
3.  Görünüm Ayarları: görünüm ayarlarını düzenlemek için.
4.  Diller: yeni dil eklemek veya mevcut dilleri düzenlemek için.
5.  Seo Yöneticisi: seo ve meta bilgilerini ve anahtar kelimeleri düzenlemek için.
6.  Şartlar ve Politika: şartlar ve politika sayfalarını düzenlemek için.
7.  E-posta Ayarları: e-posta şablonlarını düzenlemek için.
8.  SSS: sss'leri yönetmek için.
9.  Duyurular: duyuruları yönetmek için.

</section>

<section id="section-integrations">

# Entegrasyonlar

### Paypal Entegrasyonu

PayPal API Client ID ve Client Secret oluşturun:

1.  Aşağıdaki web sitesini açın [https://developer.paypal.com](https://developer.paypal.com) ve "Giriş Yap" üzerine tıklayın.
2.  Giriş yaptıktan sonra, test ödemeleri yapabilmek için bir Sandbox İşletme Hesabı oluşturun.
3.  Eğer bir sandbox hesabı oluşturduysanız, "My Apps and Credentials" menüsüne gidin ve ardından "Create App"e tıklayın.
4.  Paypal uygulamanıza bir ad verin ve önceden oluşturduğunuz geliştirici (sandbox) hesabınızı seçin. Tamamlandığında, "Create App"e tıklayın.
5.  Uygulama oluşturulduğunda, şimdi oluşturduğunuz uygulamanın ayrıntılarını göreceksiniz. Şimdi Client ID'yi ve Secret Key'i görmek için bir seçenek (Göster) bulmalısınız.
6. Canlı ve Sandbox arasında geçiş yapmak için önce sol ana menüde "My Apps & Credentials" üzerine tıklayın, ardından Canlı veya Sandbox'a tıklayın ve istediğiniz uygulamaya gidin. Unutmayın ki Sandbox ve Canlı, farklı Client ID'leri ve Secret Keys'e sahiptir.

Paypal ödeme yöntemini etkinleştirme:

1. Yönetici hesabına giriş yapın, Ödeme Yöntemlerine gidin
2. Paypal'ı seçin.
3. Paypal parametrelerinizi düzenleyin.

### Stripe Entegrasyonu

Stripe Connect Ödemeleri için Kimlik Bilgilerini Alın:

1. Stripe hesabınıza giriş yapın veya [Stripe web sitesinde](https://stripe.com/) yeni bir tane oluşturun.
2. Ayarları seçin ve ardından Stripe gösterge panelinin kenar çubuğunda API anahtarlarını seçin.
3. API anahtarları sayfasında, Yayınlanabilir anahtar ve Gizli anahtar alanlarını bulun ve değerlerini kopyalayın.

Stripe ödeme yöntemini etkinleştirme:

1. Yönetici hesabına giriş yapın, Ödeme Yöntemlerine gidin
2. Stripe'ı seçin.
3. Bu anahtarları Stripe Connect ödeme yöntemi ayarlarının ilgili alanlarına yapıştırın.

</section>

<section id="section-support">

# Destek & Talepler

Müşteri taleplerinizi yanıtlamak veya yeni talep oluşturmak için:

1. Yönetici hesabına giriş yapın, Biletler'e gidin
2. Cevaplamak için bilet seçin veya yeni bir bilet eklemek için "Yeni"ye tıklayın
3. Bilet durumu her değiştiğinde, panelinizde bildirim görürsünüz

</section>

<section class="mb-4" id="section-changelog">

# Test

Sadece test için şunları çalıştırın:

<pre>php .\vendor\bin\phpUnit</pre>

</section>

</div>

