# Turkish Wordlist (100K)

Bu projede, Türkçe diline yönelik oluşturulmuş 100.000 satırlık bir parola tahmin listesi (wordlist) yer almaktadır. Liste, günlük kullanımda sık karşılaşılan kelimeler, isimler, doğum yılları, sembol kombinasyonları ve varyasyonlardan oluşur.

## Özellikler

- Gerçek Türkçe isim ve yer adları
- Sayısal ekler ve sembollerle oluşturulmuş varyantlar
- Büyük harf ve ters yazım alternatifleri
- Brute-force ve dictionary saldırılarında etkili sonuçlar verebilir

## Kullanım Alanları

Wordlist dosyası, siber güvenlik testleri, CTF yarışmaları, parola analizleri ve eğitim amaçlı uygulamalarda kullanılabilir.

Kullanım örnekleri:

```
john --wordlist=wordlist.txt hashes.txt
hydra -L users.txt -P wordlist.txt ssh://target-ip
```

## Yapı

- `wordlist.txt`: 100.000 satırlık parola adayı listesi
- `LICENSE`: MIT Lisansı
- `.gitignore`, `CONTRIBUTING.md`: Proje standart dosyaları

## Yasal Uyarı

Bu dosya yalnızca eğitim ve etik siber güvenlik çalışmaları için hazırlanmıştır. Yetkisiz sistemlere karşı kullanımı yasal değildir ve tüm sorumluluk kullanıcıya aittir.
