# Project Overview

## Proje Tanımı

Bu proje, bir mobil oyunda yer alan **Günlük Giriş Ödül Sistemi (Daily Login Reward System)** için hazırlanmış örnek bir Business Analysis çalışmasıdır.

Sistem, oyuncuların oyuna düzenli olarak giriş yapmalarını teşvik etmek amacıyla günlük ödüller sunar. Oyuncular her gün giriş yaptıklarında belirlenen ödülü alabilir ve giriş serilerini devam ettirerek daha değerli ödüller kazanabilirler.

---

# Projenin Amacı

Bu sistemin temel amacı, oyuncuların oyuna düzenli olarak giriş yapmasını teşvik ederek oyuncu bağlılığını artırmaktır.

Sistem sayesinde;

* Günlük aktif oyuncu sayısının artırılması,
* Oyuncuların oyuna geri dönüş oranının yükseltilmesi,
* Düzenli giriş davranışının ödüllendirilmesi,
* Oyuncuların uzun vadeli etkileşiminin desteklenmesi

hedeflenmektedir.

---

# Kapsam

Bu proje aşağıdaki işlevleri kapsamaktadır.

* Oyuncunun günlük girişinin kontrol edilmesi.
* Günlük ödülün belirlenmesi.
* Ödülün oyuncuya verilmesi.
* Günlük giriş serisinin takip edilmesi.
* Giriş serisinin bozulması durumunda sıfırlanması.
* Oyuncunun mevcut seri durumunu görüntülemesi.
* Bir sonraki gün kazanılacak ödülün görüntülenmesi.

---

# Sistem Aktörleri

| Aktör        | Açıklama                                                                           |
| ------------ | ---------------------------------------------------------------------------------- |
| Oyuncu       | Günlük giriş yaparak ödül kazanan kullanıcı.                                       |
| Oyun Sistemi | Günlük girişi doğrulayan, ödülleri yöneten ve seri takibini gerçekleştiren sistem. |

---

# Varsayımlar

* Oyuncunun geçerli bir oyun hesabı bulunmaktadır.
* Oyuncu internet bağlantısına sahiptir.
* Günlük giriş bilgileri sistem tarafından güvenli şekilde saklanmaktadır.
* Her oyuncu aynı gün içerisinde yalnızca bir kez günlük ödül alabilir.

---

# Kapsam Dışı

Aşağıdaki konular bu proje kapsamında değerlendirilmemektedir.

* Oyun içi mağaza (In-Game Store)
* Battle Pass sistemi
* Başarım (Achievement) sistemi
* Loot Box (Kasa) sistemi
* Enerji (Energy) sistemi
* Çok oyunculu oyun mekanikleri

---

# Beklenen Kazanımlar

Bu sistem sayesinde oyuncuların oyuna düzenli giriş yapmaları teşvik edilir, günlük etkileşim artırılır ve uzun vadeli oyuncu bağlılığı desteklenir.
