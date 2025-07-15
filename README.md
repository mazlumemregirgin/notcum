# 📚 Notçum

**Notçum**, üniversite öğrencileri için özel olarak geliştirilmiş, not paylaşımı ve alışverişini kolaylaştıran bir platformdur. Öğrenciler ders notlarını PDF formatında yükleyebilir, bu notlar dijital olarak indirilebilir veya platforma entegre kırtasiye ortakları aracılığıyla baskılı olarak sipariş edilebilir.

---

## 🚀 Proje Amacı

Notçum'un amacı, öğrenciler arası bilgi paylaşımını artırmak, kaliteli ders materyallerine erişimi kolaylaştırmak ve öğrencilerin notlarını gelir kaynağına dönüştürmesini sağlamaktır. Aynı zamanda kırtasiyeler için de yeni bir müşteri kitlesine ulaşma fırsatı sunar.

---

## 🎯 Hedef Kitle

- 📤 **Not Yükleyen Öğrenciler** — Notlarını paylaşarak gelir elde etmek isteyen öğrenciler.
- 📥 **Not Satın Alan Öğrenciler** — Kaliteli ve özenli notlara erişmek isteyen öğrenciler.
- 🏪 **Kırtasiye Ortakları** — Öğrenciler için baskı hizmeti sunan yerel işletmeler.

---

## 🔑 Temel Özellikler

- 📄 **Not Yükleme**: Öğrenciler PDF formatında notlarını başlık, açıklama, bölüm ve fiyat bilgileri ile yükleyebilir.
- 🔍 **Not Arama ve Filtreleme**: Ders adı, kodu ve bölüme göre gelişmiş filtreleme.
- 👀 **Önizleme**: Satın almadan önce 5 rastgele sayfa gösterilir.
- 🌟 **Değerlendirme ve Yorumlar**: Kullanıcılar notları puanlayabilir ve yorum bırakabilir.
- 💾 **Dijital veya Baskılı Satın Alma**: İsteyen kullanıcılar PDF indirebilir, isteyenler kırtasiye üzerinden baskı siparişi verebilir.
- 👥 **Kullanıcı ve Kırtasiye Rolleri**: Giriş ekranında iki farklı rol ile kayıt olunabilir.

---

## 🛠️ Kullanılan Teknolojiler

| Katman        | Teknolojiler                                           |
|---------------|--------------------------------------------------------|
| Backend       | Java, Spring Boot, JPA (Hibernate), Spring MVC        |
| Frontend      | HTML, CSS, JavaScript, Thymeleaf                      |
| Veritabanı    | PostgreSQL                                             |
| Test          | JUnit, Spring Boot Test                                |
| Yardımcılar   | Lombok, Spring Boot Mail, Spring Boot Validation       |
| Geliştirme Ortamı | Postman, DBeaver                                 |

---

# 🔐 Örnek API Endpoint'leri

## 👤 Kullanıcı

| Endpoint | Açıklama |
|----------|----------|
| `POST /user/save` | Yeni kullanıcı kaydı |
| `POST /user/login` | Giriş yap |
| `GET /user/logout` | Oturumu sonlandır |
| `GET /user/current-user` | Aktif kullanıcıyı getir |

## 📓 Not

| Endpoint | Açıklama |
|----------|----------|
| `POST /note/upload` | Not yükle |
| `GET /note/get-all` | Tüm notları getir |
| `GET /note/{id}` | Belirli bir notu getir |
| `GET /note/view-pdf/{id}` | PDF içeriğini getir |

## 🛒 Sipariş

| Endpoint | Açıklama |
|----------|----------|
| `POST /order/upload` | Sipariş oluştur |
| `GET /order/stationery/{id}` | Kırtasiye siparişlerini listele |

## 📸 Uygulama Ekranları

- Ana Sayfa
- Not Yükleme Formu
- Not Detay Sayfası
- Sipariş Oluşturma Sayfası
- Profil Sayfası
- Hakkımızda / İletişim Sayfaları

## 🤝 Katkıda Bulunmak

Her katkı değerlidir. Projeyi fork'layabilir, geliştirmeler yaptıktan sonra pull request göndererek katkı sağlayabilirsiniz.

## 📬 İletişim

**Geliştirici:** Mazlum Emre Girgin

## 📝 Lisans

Bu proje MIT Lisansı ile lisanslanmıştır.
