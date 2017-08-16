0x94 Scanner v2.4

Program <b>MS-DOS ta çalışmaktadır <b>0x94 http://www.site.com yada https://www.site.com</b> şeklinde<br>

Taramak istemediginiz ozelligi <b>config.cfg</b> dosyasında  <b>True</b> yazan yerleri <b>False</b> yaparak devre dışı bırakabilirsiniz

Programdaki başlıca özellikler : 
- Sunucu IP adresi ve kullanılan protocol bilgisini alir<br>
- Sunucunun Allow Header listesini alır<br>
- Seo  yada 302 yonlendirmeli linklerin location URL lerini alır<br>
- Sitedeki tüm linkleri 3 farklı crawl yöntemiyle tamamen alır (Örümcek misali sitedeki tüm linkleri gezer)<br>
- Girdiği tüm linklerde yedek dosyaları analizi yapar<br>
- Tüm sitede Expression Language Injection dener.<br>
- Tüm sitede HTTP Response Splitting<br>
- Tüm sitede SSI(Server-Side Includes) açıklarını dener<br>
- Tüm GET ve POST verilerinde Blind LDAP injection dener<br>
- Tüm GET ve POST verilerinde Blind XPATH injection dener<br>
- Tüm GET ve POST verilerinde Remote Command Execution dener<br>
- Tüm GET ve POST verilerinde Blind Command injection dener<br>
- Tüm GET ve POST verilerinde SQL injection dener<br>
- Tüm GET ve POST verilerinde Blind SQL injection dener<br>
- Tüm GET ve POST verilerinde Time Based SQL injection dener<br>
- Tüm GET ve POST verilerinde Header injection dener<br>
- Tüm GET ve POST verilerinde Cross-Site Scripting(XSS) dener(noscript olup olmadiğini belirtir)<br>
- Tüm GET ve POST verilerinde Command injection dener<br>
- Tüm Sitede LFI denemesi yapar.<br>
- Http Trace Cross-Site Scripting açığını test eder<br>
- Tüm linklerde Header Crlf injection dener<br>
- Bulduğu site içi tüm linklerde login sayfalarini otomatik bulup basit capli brute force gerçekleştirir.<br>
- Wordpress yada Joomla siteleri tespit eder.<br>
- Tomcat kullanan siteyi tespit edip, default password denemesi yapar.<br>
- Joomla token açığını otomatik dener<br>
- Gezdiği tüm linklerde ajax ile veri gönderimi yapan URL leri tespit eder<br>
- Gezdiği tüm linklerde geçen emailleri otomatik alır<br>
- Çalışmayan(Kodları gözüken) PHP ve ASP kodlarının olduğu sayfaları tespit eder.<br>
- Gezdiği tüm linklerde OPEN Redirect açığı olup olmadığını kontrol eder<br>
- Gezdiği tüm linklerde bir alt dizine inip index Of olup olmadığını kontrol eder<br>
- Gezdiği tüm linklerde FRAME,Javascript,CSS kontrolü yapar.<br>
- Aspx siteler için Custom Error dosyası analizi yapar<br>
- Aspx siteler için Elmah Error Log  dosyası analizi yapar<br>
- Aspx siteler için Aspx Trace Information analizi yapar<br>
- Cold Fusion siteler için dizin taraması ve panel taraması yapar<br>
- Gezdiği tüm sitelerde bulunan dizinlerde aynı zamanda CSS ve Javascript dizinlerinde Shell taraması yapar <br>
- Gezdiği tüm linklerin yedek dosyası kontrolünü yapar<br>
- Site içerisindeki tüm dizinlerde yedeklenmiş dosya yada bilgi dosyaları (rar,zip,tar,tar.gz,txt,sql) kontrolü yapar<br>
- Site içerisinde dosya upload izni olan sayfaları bulur<br>
- ShellShock açığını test eder<br>
- Apache Strus açığını test eder<br>
- SEF url sistemi olan sitelerde SEF url adreslerine göre Cross-Site Scripting(XSS) denemesi yapar.<br>

Javascript destekler.<br>
Asp.net ve Java siteler için ignoreparametre(taramaya dahil etme) özelliği ignoreparametre.txt den ayarlanabilir.<br>

<br>Config.cfg dosyasından : </b><br>
Thread sayısı,<br>
Cookie ayarı (Login olupta işlem yapabilir),<br>
Proxy ayarı,<br>
ve birden fazla Request engelleyen siteler için Request bekleme limiti ayarlanabilir<br>

/*****/ Programda eklemediğimiz halen bir çok şey mevcuttur /****/

<b>SADECE Güvenlik testleri için kullanın</b>

<b>TÜRK sitelerinde tarama yapmaz</b>

<a href="https://github.com/antichown/0x94scanner">0x94 Scanner</a>

<a href="https://twitter.com/0x94">Twitter 0x94</a>
