# Functional Requirements

## Amaç

Bu doküman, Günlük Giriş Ödül Sistemi'nin sağlaması gereken fonksiyonel gereksinimleri tanımlamak amacıyla hazırlanmıştır.

---

# Functional Requirements

| ID    | Fonksiyonel Gereksinim                                                                     | Öncelik |
| ----- | ------------------------------------------------------------------------------------------ | ------- |
| FR-01 | Sistem, oyuncunun günlük giriş yaptığını doğrulamalıdır.                                   | Yüksek  |
| FR-02 | Sistem, oyuncunun aynı gün içerisinde daha önce ödül alıp almadığını kontrol etmelidir.    | Yüksek  |
| FR-03 | Sistem, uygun oyuncuya o güne ait ödülü vermelidir.                                        | Yüksek  |
| FR-04 | Sistem, ödülü oyuncunun envanterine eklemelidir.                                           | Yüksek  |
| FR-05 | Sistem, oyuncunun günlük giriş serisini güncellemelidir.                                   | Yüksek  |
| FR-06 | Sistem, oyuncunun mevcut giriş serisini görüntüleyebilmelidir.                             | Orta    |
| FR-07 | Sistem, oyuncunun bir sonraki gün kazanacağı ödülü görüntüleyebilmelidir.                  | Orta    |
| FR-08 | Sistem, giriş serisi kesildiğinde seri bilgisini sıfırlamalıdır.                           | Yüksek  |
| FR-09 | Sistem, ödül alma işlemi tamamlandıktan sonra oyuncuya bilgilendirme mesajı göstermelidir. | Orta    |
| FR-10 | Sistem, geçersiz veya tekrar eden ödül taleplerini reddetmelidir.                          | Yüksek  |

---

# Fonksiyonel Kapsam

Sistem aşağıdaki temel işlevleri yerine getirmelidir.

* Günlük girişi doğrulamak.
* Günlük ödülü belirlemek.
* Ödülü oyuncuya vermek.
* Oyuncunun giriş serisini takip etmek.
* Seri bilgisini güncellemek.
* Oyuncuya mevcut ilerleme durumunu göstermek.
* Sonraki ödül hakkında bilgi sunmak.

---

# Bağımlılıklar

Fonksiyonel gereksinimlerin doğru şekilde çalışabilmesi için aşağıdaki bileşenlerin hazır olduğu varsayılmaktadır.

* Oyuncunun aktif bir oyun hesabına sahip olması.
* Oyuncu envanter sisteminin kullanılabilir durumda olması.
* Günlük ödül takviminin sistemde tanımlanmış olması.
* Günlük giriş bilgilerinin güvenli şekilde saklanması.
