# Öğrenci Kaynak Rehberi

Git ve GitHub atölyesi için ortak öğrenci kaynak rehberi.

## Atölye görevi · Bir commit seç ve incele

Görev bireysel ve yaklaşık 30 dakika sürer. Tüm adımları tarayıcıda yapabilirsin.

### 1. Bir commit seç

[Commit geçmişini](https://github.com/asimisik9/ogrenci-kaynak-rehberi/commits/main/) aç. Beş Python örneğinden birinin commit’ini seç: ekrana yazdırma, değişkenler, toplama, `if` veya `for`. İstersen **Git başlangıç kaynağını güncelle** commit’ini de seçebilirsin. Birden fazla kişi aynı commit’i inceleyebilir.

Seçtiğin commit’i aç ve hangi dosyanın eklendiğini veya değiştiğini bul. Değişikliği kendi cümlelerinle açıkla. Python örneği seçtiysen ekrana ne yazdıracağını tahmin et. Kaynak güncellemesini seçtiysen eski ve yeni bağlantıyı belirt.

### 2. Bulgularını pull request ile gönder

1. Ortak repoyu fork et ve kendi fork’unda `inceleme/<github-kullanici-adin>` dalını aç.
2. Bu dalda `incelemeler/<github-kullanici-adin>.md` dosyasını oluştur ve aşağıdaki şablonu doldur. Yer tutucuyu kendi GitHub kullanıcı adınla değiştir.
3. Dosyanı commit et ve kendi dalından ortak reponun `main` dalına pull request aç. Örnek PR başlığı: **Commit incelemesi — kullanici-adin**.

```markdown
# Commit incelemesi

- Seçtiğim commit (başlık ve bağlantı):
- Eklenen veya değişen dosya:
- Bu commit’te ne yapıldı?
- Beklenen ekran çıktısı veya eski ve yeni bağlantı:
```

### 3. Bir arkadaşının katkısını incele

PR bağlantılarınızı paylaşın. Arkadaşının PR’ındaki **Files changed** sekmesinden inceleme dosyasını aç ve bulgularını seçtiği commit ile karşılaştır. Doğruladığın bir bulguyu veya düzeltilecek bir noktayı yorum olarak yaz.

Görev sonunda ortak repoda kendi PR’ın ve başka bir katılımcının PR’ında bir inceleme yorumun olmalı.
