# Business Rules

## Amaç

Bu doküman, Günlük Giriş Ödül Sistemi'nin uyması gereken iş kurallarını tanımlamak amacıyla hazırlanmıştır.

---

# Business Rules

| ID    | İş Kuralı                                                                                                     | Gerekçe                                                 |
| ----- | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| BR-01 | Her oyuncu bir takvim günü içerisinde yalnızca bir kez günlük ödül alabilir.                                  | Aynı gün birden fazla ödül alınmasını önlemek.          |
| BR-02 | Günlük ödül yalnızca oyuna giriş yapan oyuncular tarafından alınabilir.                                       | Sistemin amacına uygun kullanım sağlamak.               |
| BR-03 | Günlük ödüller önceden tanımlanmış ödül takvimine göre dağıtılmalıdır.                                        | Tüm oyuncular için tutarlı bir ödül sistemi oluşturmak. |
| BR-04 | Oyuncunun giriş serisi her başarılı günlük ödül alımından sonra bir gün artırılmalıdır.                       | Düzenli giriş davranışını teşvik etmek.                 |
| BR-05 | Oyuncu bir günü kaçırırsa giriş serisi sıfırlanmalıdır.                                                       | Günlük giriş alışkanlığını desteklemek.                 |
| BR-06 | Günlük ödül başarıyla verildiğinde ödül oyuncunun envanterine eklenmelidir.                                   | Oyuncunun ödülünü kullanabilmesini sağlamak.            |
| BR-07 | Oyuncu aynı gün ikinci kez ödül almaya çalışırsa sistem ödül vermemeli ve bilgilendirme mesajı göstermelidir. | Hatalı veya kötüye kullanımı önlemek.                   |
| BR-08 | Oyuncu günlük giriş ekranında mevcut seri gününü görüntüleyebilmelidir.                                       | Oyuncunun ilerlemesini takip edebilmesini sağlamak.     |
| BR-09 | Oyuncu günlük giriş ekranında bir sonraki gün kazanacağı ödülü görüntüleyebilmelidir.                         | Oyuncunun oyuna tekrar giriş yapmasını teşvik etmek.    |
| BR-10 | Günlük ödül sistemi tüm oyuncular için aynı kuralları uygulamalıdır.                                          | Adil ve tutarlı bir oyun deneyimi sunmak.               |

---

# İş Kurallarına İlişkin Notlar

* Günlük ödül sistemi yalnızca aktif oyuncu hesapları için geçerlidir.
* Günlük ödül takvimi oyun yönetimi tarafından önceden tanımlanır.
* İş kurallarında yapılacak değişiklikler tüm oyuncular için aynı anda geçerli olur.
