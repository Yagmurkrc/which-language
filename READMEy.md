# Mini Notes Project 📝

Bu proje, komut satırı üzerinden çalışan basit bir not alma uygulamasıdır.

## V1 Geliştirmeleri (V0 -> V1 Farkları)
Ödevin V1 aşaması kapsamında aşağıdaki güncellemeler yapılmıştır:

1. **Dil Güncellemesi:** Tüm kullanıcı mesajları ve hata bildirimleri Türkçeleştirilerek kullanım kolaylığı sağlandı.
2. **Öncelik Sistemi:** Not oluştururken artık `Düşük`, `Orta` veya `Yüksek` gibi öncelik seviyeleri eklenebiliyor.
3. **Veri Doğrulama:** Başlık veya içerik boş bırakıldığında uygulamanın hata vermesi ve kullanıcıyı uyarması sağlandı.

## Kurulum ve Kullanım
Uygulamayı başlatmak için:
`python solution_v1.py init`

Not eklemek için:
`python solution_v1.py create "Başlık" "İçerik" "Yüksek"`
