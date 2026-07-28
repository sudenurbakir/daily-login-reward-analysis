# Acceptance Criteria

## Amaç

Bu doküman, Günlük Giriş Ödül Sistemi kapsamında tanımlanan kullanıcı hikayelerinin kabul kriterlerini açıklamak amacıyla hazırlanmıştır.

---

# Acceptance Criteria

## US-01 - Günlük Ödül Alma

**Given** oyuncu oyuna giriş yapmıştır ve o gün henüz ödül almamıştır.

**When** oyuncu günlük ödülünü talep eder.

**Then** sistem o güne ait ödülü oyuncuya vermeli ve ödülü envantere eklemelidir.

---

## US-02 - Giriş Serisini Görüntüleme

**Given** oyuncunun aktif bir günlük giriş serisi bulunmaktadır.

**When** oyuncu günlük giriş ekranını görüntüler.

**Then** sistem oyuncunun mevcut giriş serisini göstermelidir.

---

## US-03 - Sonraki Günün Ödülünü Görüntüleme

**Given** oyuncu günlük giriş ekranını açmıştır.

**When** sistem ödül takvimini görüntüler.

**Then** oyuncuya bir sonraki gün kazanacağı ödül gösterilmelidir.

---

## US-04 - Ödülün Envantere Eklenmesi

**Given** oyuncu günlük ödül almaya hak kazanmıştır.

**When** ödül başarıyla verilir.

**Then** sistem ödülü oyuncunun envanterine eklemeli ve başarı mesajı göstermelidir.

---

## US-05 - Aynı Gün Tekrar Ödül Alma Girişimi

**Given** oyuncu aynı gün içerisinde günlük ödülünü almıştır.

**When** oyuncu tekrar ödül almaya çalışır.

**Then** sistem yeni bir ödül vermemeli ve oyuncuyu uygun bir mesaj ile bilgilendirmelidir.

---

## US-06 - Giriş Serisinin Bozulması

**Given** oyuncu günlük giriş serisini devam ettirememiştir.

**When** sistem oyuncunun giriş durumunu kontrol eder.

**Then** oyuncunun giriş serisi sıfırlanmalı ve sistem güncel seri bilgisini göstermelidir.

---

## US-07 - Adil Ödül Dağıtımı

**Given** tüm oyuncular aynı günlük ödül sistemini kullanmaktadır.

**When** oyuncular günlük ödüllerini alırlar.

**Then** sistem tanımlanan iş kurallarını tüm oyuncular için tutarlı şekilde uygulamalıdır.
