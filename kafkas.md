Proje Adı: Aetheria - AI Destekli Web Sitesi Prompt Üreticisi
Rolün: Sen, Gemini 2.5 Flash Preview 05-20, deneyimli bir full-stack web geliştiricisi, UI/UX tasarımcısı ve AI etkileşim uzmanısın. Görevin, "Aetheria" adlı bir web uygulamasını tasarlamak ve geliştirmek için gerekli tüm adımları, kod yapılarını ve tasarım prensiplerini detaylandırmak.
Aetheria'nın Temel Amacı:
Aetheria, kullanıcıların başka web siteleri oluşturmak üzere AI modellerine (özellikle Gemini 2.5 Flash Preview 05-20 gibi modellere) sunabilecekleri yüksek kaliteli, detaylı ve etkili promptlar oluşturmalarına yardımcı olan bir web aracıdır. Kullanıcılar, Aetheria'ya hedefledikleri web sitesinin özelliklerini, amacını ve stilini basitçe anlatacak, Aetheria ise bu girdileri optimize edilmiş bir AI promptuna dönüştürecektir.
Hedef Kitle (Aetheria Kullanıcıları):
Web sitesi oluşturmak isteyen ancak etkili AI promptları yazmakta zorlanan geliştiriciler, tasarımcılar, girişimciler ve hobi amaçlı kullanıcılar.
Kullanılacak Teknolojiler (Aetheria için):
Frontend:
HTML5 (Semantik etiketler)
CSS3 (Modern layout teknikleri: Flexbox, Grid; Animasyonlar, Geçişler)
JavaScript (ES6+; DOM manipülasyonu, olay yönetimi, API çağrıları (gerekirse), ve dinamik prompt oluşturma mantığı)
Backend:
Python (Flask veya Django tercih edilebilir, Flask daha hafif olduğu için bu proje için daha uygun olabilir).
Backend, kullanıcı girdilerini almak, gerekirse işlemek ve prompt oluşturma mantığının bir kısmını barındırmak için kullanılabilir (alternatif olarak, prompt oluşturma tamamen client-side JS ile de yapılabilir).
İkonlar: Font Awesome, Material Icons veya SVG tabanlı özel ikonlar.
Animasyon Kütüphaneleri (Opsiyonel ama Tavsiye Edilir): GSAP (GreenSock Animation Platform), Anime.js veya saf CSS animasyonları (performans odaklı).
Aetheria Web Sitesinin Tasarım ve Kullanıcı Deneyimi (UX) Özellikleri:
Genel Estetik: Modern, şık, fütüristik ama kullanıcı dostu bir "eterik" (Aetheria adına uygun) tema. Teknoloji ve yaratıcılığı yansıtmalı.
Renk Paleti:
Ana Renkler: Koyu mavi (#1A237E), derin mor (#4A148C) veya gece mavisi (#0D1B2A) gibi koyu tonlar.
Vurgu Renkleri: Elektrik mavisi (#00FFFF), parlak pembe/mor (#E040FB) veya gümüş/altın tonları (#C0C0C0, #FFD700).
Nötr Renkler: Açık gri (#F5F5F5) ve koyu gri (#212121) tonları.
Degrade (Gradient) kullanımı: Ana ve vurgu renkleri arasında yumuşak geçişler.
Tipografi:
Başlıklar: Modern, geometrik bir sans-serif font (Örn: Montserrat, Poppins, Exo 2).
Paragraf Metinleri: Yüksek okunabilirliğe sahip, temiz bir sans-serif font (Örn: Open Sans, Lato, Roboto).
Layout:
Tamamen duyarlı (responsive) tasarım (Mobil, Tablet, Masaüstü).
Temiz, organize ve sezgisel arayüz. Gereksiz karmaşadan kaçınılmalı.
Bol beyaz alan (negatif boşluk) kullanımı.
İkonografi:
Minimalist, çizgi tabanlı (line-icon) veya düz (flat) stil ikonlar.
İkonlar, işlevselliklerini net bir şekilde yansıtmalı.
Animasyonlar ve Efektler:
Sayfa Yükleme Animasyonu: Hafif, estetik bir preloader (örneğin, Aetheria logosunun stilize bir animasyonu veya soyut geometrik şekiller).
Hover Efektleri: Butonlar, linkler ve interaktif kartlar üzerinde zarif hover efektleri (renk değişimi, hafif büyüme, gölge efekti).
Form Elemanları: Seçildiğinde (focus) belirginleşen, kullanıcı dostu form elemanları.
Prompt Üretimi Animasyonu: "Üret" butonuna tıklandığında, promptun oluştuğunu gösteren kısa, tatmin edici bir animasyon (örneğin, metnin harf harf yazılması veya bir "düşünme" animasyonu).
Scroll Animasyonları (İsteğe Bağlı): Sayfa kaydırıldıkça elementlerin yumuşak bir şekilde görünmesi (fade-in, slide-in).
Parçacık Efektleri (İsteğe Bağlı): Arka planda, performansı etkilemeyecek şekilde, Aetheria'nın "eterik" temasına uygun ince, hareketli parçacıklar veya soyut çizgiler.
Modal Animasyonları: Ayarlar veya ek bilgi pencereleri açılırken yumuşak geçişler.
Aetheria'nın Sayfa Yapısı ve İşlevleri:
Ana Sayfa (Tek Sayfa Uygulaması - SPA veya Çok Sayfalı olabilir, SPA tercih edilir):
Header:
Sol tarafta "Aetheria" logosu (stilize, modern).
Sağ tarafta opsiyonel olarak "Hakkında", "Nasıl Kullanılır?" gibi basit navigasyon linkleri veya bir ayar ikonu.
Hero Bölümü (Giriş Alanı):
Etkileyici bir başlık: "Yaratıcılığınızı Serbest Bırakın: AI İçin Mükemmel Web Sitesi Promptları Oluşturun."
Kısa bir açıklama: "Aetheria, hayalinizdeki web sitesini AI'a anlatmanın en kolay yolu. Sadece fikirlerinizi girin, biz sizin için en etkili promptu hazırlayalım."
Prompt Oluşturma Arayüzü (Ana İşlevsellik):
Girdi Alanları (Form): Kullanıcının hedeflediği web sitesi hakkında bilgi gireceği alanlar. Her alanın yanında açıklayıcı tooltip ikonları (?) olabilir.
input_website_purpose: "Web Sitenizin Temel Amacı Nedir?" (Örn: E-ticaret, blog, portfolyo, kurumsal tanıtım vb.) - (Textarea)
input_target_audience: "Hedef Kitleniz Kimler?" (Örn: Genç profesyoneller, sanatçılar, küçük işletmeler vb.) - (Text input)
input_key_features: "Sitenizde Olmasını İstediğiniz Ana Özellikler Nelerdir?" ( Virgülle ayrılmış liste veya etiket girişi. Örn: Ürün listeleme, blog bölümü, iletişim formu, kullanıcı girişi, galeri) - (Textarea veya tag input)
input_design_style: "Tercih Ettiğiniz Tasarım Stili?" (Seçenekler: Minimalist, Modern, Kurumsal, Eğlenceli, Vintage, Karanlık Tema, Aydınlık Tema vb.) - (Dropdown veya radio buttons)
input_color_preferences: "Renk Tercihleriniz Var Mı?" (Örn: Mavi ve beyaz tonları, canlı renkler, pastel tonlar) - (Text input veya renk seçici)
input_inspirations: "Beğendiğiniz Örnek Siteler veya Tasarımlar Var Mı? (Link veya açıklama)" - (Textarea, opsiyonel)
input_tech_stack_preference (Opsiyonel): "Hedef site için AI'dan önermesini istediğiniz özel teknolojiler var mı?" (Örn: React, Vue, Python/Django, WordPress) - (Text input)
input_ai_model_target: "Hangi AI Modeli İçin Prompt Oluşturulsun?" (Başlangıçta sadece "Gemini 2.5 Flash Preview 05-20" seçeneği olabilir, ileride genişletilebilir) - (Dropdown, varsayılan olarak seçili)
"Prompt Oluştur" Butonu: Büyük, dikkat çekici ve animasyonlu bir buton.
Prompt Çıktı Alanı:
"Oluşturulan Prompt:" başlığı.
Geniş bir metin alanı (textarea veya pre etiketi içinde code etiketi), oluşturulan promptun okunabilir bir şekilde gösterildiği yer.
"Promptu Kopyala" butonu (ikonlu ve işlevsel).
(Opsiyonel) "Promptu Düzenle" butonu.
Örnek Kullanımlar / İpuçları Bölümü (Opsiyonel):
Kullanıcılara ilham verecek birkaç örnek prompt senaryosu.
Daha iyi promptlar için ipuçları.
Footer:
Telif hakkı bilgisi "© [Yıl] Aetheria".
Belki küçük bir "Gemini 2.5 Flash Preview 05-20 ile güçlendirilmiştir" notu (eğer Aetheria'nın kendisi de Gemini kullanıyorsa bu anlamlı olur, yoksa "Gemini 2.5 Flash Preview 05-20 için prompt üretir" daha doğru).
Prompt Oluşturma Mantığı (JavaScript veya Python'da):
Kullanıcının girdiği verileri alıp, aşağıdaki gibi yapılandırılmış bir metin şablonuna yerleştirecek bir fonksiyon:
"PROMPT BAŞLANGICI

**Proje Adı:** [Kullanıcının Belirteceği Bir Proje Adı veya Genel Bir İsim]

**Rolün:** Sen, Gemini 2.5 Flash Preview 05-20, deneyimli bir web geliştirici ve UI/UX tasarımcısın. Amacın, aşağıda detayları verilen web sitesini HTML, CSS, JavaScript ve [Kullanıcının Belirttiği Backend Teknolojisi veya Genel Öneri] kullanarak oluşturmak.

**Web Sitesinin Temel Amacı:**
{input_website_purpose}

**Hedef Kitle:**
{input_target_audience}

**Anahtar Özellikler:**
{input_key_features}

**Tasarım Stili ve Tercihleri:**
*   Genel Stil: {input_design_style}
*   Renk Paleti: {input_color_preferences}
*   İlham Alınan Siteler/Tasarımlar (varsa): {input_inspirations}
*   Ek Notlar: Modern, kullanıcı dostu ve {input_design_style}'a uygun ikonlar, animasyonlar ve efektler kullanılmalı. Site tamamen duyarlı olmalıdır.

**Teknoloji Tercihleri (varsa):**
{input_tech_stack_preference}

**Beklenen Çıktılar:**
1.  Ana sayfa ve belirtilen özelliklere sahip alt sayfalar için HTML yapıları.
2.  Belirtilen tasarım stiline uygun, duyarlı CSS kodları (animasyonlar ve geçişler dahil).
3.  Gerekli interaktivite için JavaScript kodları.
4.  [Eğer backend belirtildiyse] Backend için temel dosya yapısı ve endpoint tanımlamaları.
5.  Kullanılacak ikon setleri ve fontlar için öneriler.
6.  Genel tasarım ve geliştirme süreci hakkında açıklamalar ve en iyi uygulamalar.

Mümkün olan en kaliteli, modern ve etkili web sitesini oluşturmak için yaratıcılığını kullan.

PROMPT SONU"
Use code with caution.
Backend (Python - Flask Örneği):
Eğer prompt oluşturma backend'de yapılacaksa:
/generate_prompt (POST): Kullanıcı girdilerini JSON olarak alır, yukarıdaki mantıkla promptu oluşturur ve JSON olarak geri döner.
Ana sayfa için / (GET) endpoint'i.
Statik dosyalar (CSS, JS, Resimler) için yapılandırma.
Senden Beklenenler (Gemini 2.5 Flash Preview 05-20):
Dosya Yapısı Önerisi: Aetheria projesi için ideal bir klasör ve dosya yapısı (örn: /static/css, /static/js, /static/img, /templates, app.py).
HTML Şablonları: Ana sayfa (index.html) ve gerekirse diğer bileşenler için semantik HTML yapıları.
CSS Kodları: Belirtilen estetik, renk paleti, tipografi ve layout (Flexbox/Grid) prensiplerine uygun, duyarlı CSS kodları. İstenen animasyonlar ve efektler için CSS örnekleri veya kütüphane entegrasyonu önerileri.
JavaScript Kodları:
DOM manipülasyonu (girdi alma, çıktı gösterme).
Form doğrulama (temel düzeyde).
Prompt oluşturma mantığının client-side implementasyonu (veya backend ile iletişim).
"Promptu Kopyala" işlevselliği.
Belirtilen animasyonların tetiklenmesi.
Python (Flask/Django) Kodları:
Temel uygulama kurulumu (app.py).
Route tanımlamaları.
Eğer prompt oluşturma backend'de ise, ilgili fonksiyon.
İkon ve Animasyon Entegrasyonu: Hangi ikon kütüphanesinin nasıl entegre edileceği ve temel animasyonların nasıl uygulanacağına dair rehberlik.
Açıklamalar ve En İyi Uygulamalar: Kodun önemli kısımları için açıklamalar, performans optimizasyonu, erişilebilirlik (WCAG) ve güvenlik konularında temel öneriler.
Ek Notlar:
Aetheria'nın kendisi, kullanıcıya ilham verecek şekilde şık ve modern olmalıdır.
Kullanıcı deneyimi (UX) akıcı ve sezgisel olmalıdır.
Performans optimizasyonuna dikkat et (özellikle animasyonlar ve client-side JS için).
Bu detaylı prompt ile Aetheria projesini hayata geçirmek için gerekli tüm bilgileri ve adımları oluşturmanı bekliyorum. Yaratıcılığını ve uzmanlığını kullanarak Aetheria'yı etkileyici bir araç haline getir.
