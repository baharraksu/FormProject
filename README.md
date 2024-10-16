Bu proje, bir İş Başvuru Formu'nu içeriyor ve HTML ve CSS kullanılarak oluşturulmuş bir form arayüzüdür. Form, kullanıcılardan çeşitli bilgileri toplamak için yapılandırılmış ve modern bir tasarımla stilize edilmiştir. Proje hem işlevsel hem de estetik açıdan dikkatlice tasarlanmıştır.

Aşağıda bu projeyi detaylıca açıklayacağım:

1. Genel Yapı
Projenin temel yapısı HTML ile oluşturulmuştur ve bu form kullanıcılardan belirli bilgileri toplamak için tasarlanmıştır.
CSS ile stil verilerek formun görselliği geliştirilmiş, kullanıcı dostu bir arayüz yaratılmıştır.
2. HTML Yapısı
HTML, kullanıcıdan veri toplamak için gereken alanların hepsini içerir.

2.1. Başlık
etiketi kullanılarak "İş Başvuru Formu" başlığı oluşturulmuş ve bu başlık ortalanmıştır.
2.2. Form Alanları
Formda kullanıcıdan toplanacak bilgiler şunlardır:

Ad Soyad:
input türünde bir metin alanı (type="text") kullanılarak kullanıcının adını ve soyadını girmesi sağlanır.

Telefon Numarası:
input[type="tel"] ile kullanıcının telefon numarasını girmesi istenir. Regex (regular expression) ve pattern ile telefon numarasının doğruluğu (10 haneli olması gerektiği) kontrol edilir.

E-Posta:
input[type="email"] alanı ile kullanıcının e-posta adresi alınır. HTML5 özelliği sayesinde e-posta formatı otomatik olarak kontrol edilir.
Doğum Tarihi:

input[type="date"] ile doğum tarihi seçimi yapılır.

Cinsiyet:
input[type="radio"] ile cinsiyet seçimi yapılır. Kullanıcı erkek veya kadın seçeneklerinden birini seçebilir.

T.C. Kimlik No:
input[type="tc"] ile kimlik numarası girilmesi sağlanır. Yine bir regex ile kimlik numarasının 11 haneli olup olmadığı kontrol edilir.

Medeni Durum:
Yine input[type="radio"] seçenekleri ile medeni durum bilgisi alınır.

Üniversite:
select ve option etiketleriyle kullanıcıya bir liste sunulur ve buradan üniversite seçimi yapılır.

Şehir:
input[list="cities"] ve datalist kullanılarak kullanıcıya bir şehir listesi sunulur ve kullanıcı burada şehir seçimini yapar.
Programlama Bilgisi:

input[type="checkbox"] ile kullanıcı bildiği programlama dillerini işaretleyebilir. C#, Python, Node.js, Golang gibi diller burada listelenmiştir.

Ön Yazı:
Kullanıcıdan daha detaylı bilgi almak için textarea kullanılmıştır. Kullanıcı bu alana bir ön yazı girebilir.

Yabancı Dil Bilgisi:
input[type="range"] ile kullanıcının İngilizce ve Almanca dil bilgisi derecelendirilir (1 ile 5 arası bir değer).

Bize Nereden Ulaştınız:
input[type="radio"] ile kullanıcının formu nereden duyduğuna dair bilgi toplanır (LinkedIn, Instagram vb.).

CV Yükle:
input[type="file"] ile kullanıcıdan CV yüklemesi istenir.
2.3. Dosya ve Görsel Yükleme

Görsel Yükleme: Formun sağ üst köşesinde, kullanıcıdan profil resmi ya da başka bir görsel yüklemesi istenmiştir. Bu alan input[type="file"] ile sağlanmıştır.
CV Yükleme: Kullanıcıların CV dosyalarını yükleyebilecekleri bir input[type="file"] alanı oluşturulmuştur.

2.4. Butonlar
Gönder: input[type="submit"] ile kullanıcı formu doldurduktan sonra verileri gönderebilir.
Temizle: input[type="reset"] ile kullanıcı formdaki verileri temizleyebilir.



