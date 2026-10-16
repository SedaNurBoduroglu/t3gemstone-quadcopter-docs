<p align="center">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/t3gemstone/docs/main/logo/dark.png" width="40%" />
        <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/t3gemstone/docs/main/logo/light.png" width="40%" />
        <img alt="T3 Foundation" src="https://raw.githubusercontent.com/t3gemstone/docs/main/logo/light.png" width="40%" />
    </picture>
</p>

# T3 Gemstone İHA — Eğitim ve Yapım Dokümantasyonu

<p align="center">
  <a href="https://github.com/SedaNurBoduroglu/t3gemstone-quadcopter-docs"><img alt="Docs repo" src="https://img.shields.io/badge/Docs-repo-red.svg"></a>
  <a href="kaynak-sunumlar"><img alt="Kaynak sunumlar" src="https://img.shields.io/badge/Kaynak-sunumlar-black.svg"></a>
  <a href="https://docs.t3gemstone.org"><img alt="T3 Gemstone Docs" src="https://img.shields.io/badge/T3_Gemstone-docs-blue.svg"></a>
</p>

> T3 Gemstone kartı kullanılarak bir İnsansız Hava Aracı (İHA/drone)
> tasarlamak ve inşa etmek isteyenler için hazırlanmış eğitim
> dokümantasyonu.

## Hızlı Başlangıç

- [1. Giriş: İHA Nedir, Türleri ve Temel Alt Sistemler](docs/01-giris-ve-iha-turleri.md)
- [Tüm dokümanlar](docs)
- [Orijinal sunumlar](kaynak-sunumlar)

## Kapsam

- İHA türleri ve İHA'nın temel alt sistemleri
- Mekanik temeller: eksenler, bileşenler, itki-kuvvet dengesi, aerodinamik
- Aviyonik ve güç sistemleri: motor/ESC/pervane seçimi, batarya hesaplamaları
- Yazılım ve kontrol mantığı: sensör verisi, PID algoritması, ArduPilot ve ChibiOS
- T3 Gemstone O1 üzerinde ArduPilot çalıştırmanın iki yaklaşımı (Linux/A53 ve ChibiOS/R5F)
- Parça seçimi, montaj ve uçtan uca tasarım süreci
- T3 Gemstone O1 kartı üzerinde ArduPilot ile aviyonik mimarisi
- Örnek yapılandırmalar (BOM), ileri seviye eklentiler ve yapay zeka ile otonom görevler için gelecek çalışma fikirleri

T3 Gemstone kartının kurulumu (imaj yazma, ilk açılış vb.) gibi genel
konularda T3'ün resmi dokümantasyonuna yönlendiriyoruz:
[docs.t3gemstone.org](https://docs.t3gemstone.org). Bu doküman
yalnızca İHA'ya özgü teori, tasarım kararları ve parça seçimi konularına
odaklanır.

## İçindekiler

### Temel Kavramlar

- [1. Giriş: İHA Nedir, Türleri ve Temel Alt Sistemler](docs/01-giris-ve-iha-turleri.md)
- [2. Mekanik Temeller](docs/02-mekanik-temelleri.md)
- [3. Aviyonik ve Güç Sistemleri](docs/03-aviyonik-ve-guc-sistemleri.md)
- [4. Yazılım ve Kontrol Mantığı](docs/04-yazilim-ve-kontrol-mantigi.md)

### Uygulama

- [5. Parça Seçimi, Montaj ve Tasarım Süreci](docs/05-parca-secimi-montaj-ve-tasarim-sureci.md)
- [6. T3 Gemstone O1 ile Aviyonik Mimarisi](docs/06-t3-gemstone-o1-mimarisi.md)
- [7. Örnek Yapılandırmalar ve İleri Seviye Eklentiler](docs/07-ornek-yapilandirmalar-ve-eklentiler.md)

### Referans

- [8. Kaynakça](docs/08-kaynakca.md)

## Nasıl Okunmalı?

Dokümanlar sırayla okunacak şekilde tasarlanmıştır; her dosyanın
sonunda bir sonraki bölüme yönlendiren bir bağlantı bulunur. İlk kez
bir İHA tasarlayacaklar için 1'den 7'ye kadar sırayla okumak,
doğrudan T3 Gemstone O1'e özgü donanım bilgisine ulaşmak isteyenler
için ise doğrudan [6. bölüme](docs/06-t3-gemstone-o1-mimarisi.md)
geçmek önerilir.

## Katkı

Bir hata fark ederseniz veya eksik bir konu eklemek isterseniz, ilgili
`docs/*.md` dosyasını düzenleyip bir pull request açabilirsiniz.
