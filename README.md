# 📚 Notçum

**Notçum** is a specialized platform designed to simplify and enhance the sharing and exchange of class notes among university students. Students can upload their notes in PDF format, and others can either download them digitally or order printed versions through our integrated stationery partners.

---

## 🚀 Project Purpose

The goal of Notçum is to boost knowledge sharing among students, improve access to quality course materials, and enable students to turn their notes into a source of income. Additionally, it offers local stationery businesses an opportunity to reach a new customer base.

---

## 🎯 Target Audience

- 📤 **Note Uploaders** — Students who want to earn income by sharing their course notes.
- 📥 **Note Buyers** — Students looking for well-organized and high-quality notes to study from.
- 🏪 **Stationery Partners** — Local businesses that provide printing services for ordered notes.

---

## 🔑 Key Features

- 📄 **Note Uploading**: Students can upload their notes in PDF format along with the title, description, department, and price.
- 🔍 **Note Search and Filtering**: Advanced filtering by course name, code, and department.
- 👀 **Preview Before Purchase**: Users can preview 5 randomly selected pages before buying.
- 🌟 **Ratings and Reviews**: Users can rate notes and leave comments to help others.
- 💾 **Digital or Printed Versions**: Buyers can either download the notes or have them printed by a partner stationery store.
- 👥 **User and Stationery Roles**: Separate registration and login flows for students and stationery accounts.

---

## 🛠️ Technologies Used

| Layer         | Technologies                                           |
|---------------|--------------------------------------------------------|
| Backend       | Java, Spring Boot, JPA (Hibernate), Spring MVC        |
| Frontend      | HTML, CSS, JavaScript, Thymeleaf                      |
| Database      | PostgreSQL                                             |
| Testing       | JUnit, Spring Boot Test                                |
| Utilities     | Lombok, Spring Boot Mail, Spring Boot Validation       |
| Dev Tools     | Postman, DBeaver                                       |

---

# 🔐 Sample API Endpoints

## 👤 User

| Endpoint | Description |
|----------|-------------|
| `POST /user/save` | Register a new user |
| `POST /user/login` | Log in as a user |
| `GET /user/logout` | Log out the session |
| `GET /user/current-user` | Retrieve the currently logged-in user |

## 📓 Note

| Endpoint | Description |
|----------|-------------|
| `POST /note/upload` | Upload a new note |
| `GET /note/get-all` | Get all notes |
| `GET /note/{id}` | Get a note by ID |
| `GET /note/view-pdf/{id}` | View note PDF |

## 🛒 Order

| Endpoint | Description |
|----------|-------------|
| `POST /order/upload` | Create an order |
| `GET /order/stationery/{id}` | Get orders for a stationery |

---

## 📸 Application Screens

- Homepage  
- Note Upload Form  
- Note Detail Page  
- Order Creation Page  
- Profile Page  
- About Us / Contact Us Pages

---

## 🤝 Contributing

All contributions are welcome! Feel free to fork the project, make improvements, and submit a pull request.

---

## 📬 Contact

**Developer:** Mazlum Emre Girgin

[LinkedIn Profile](https://www.linkedin.com/in/mazlum-emre-girgin/)

---

## 📝 License

This project is licensed under the MIT License.


---

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
