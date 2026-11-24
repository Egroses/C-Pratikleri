# C Programlama Pratikleri

Programlamaya C ile başlanan ilk yılın çalışma defteri: Eylül 2020 – Nisan 2021 arasında yazılmış, her biri tek bir konuyu deneyen 140'tan fazla küçük program.

## Neden?

Bir dili gerçekten öğrenmenin yolu, her kavramı küçük bir programda tek tek denemekten geçiyor. Bu repo o sürecin kaydı: döngülerden pointer'lara, dinamik bellekten dosya işlemlerine kadar her konu ayrı bir klasörde, çoğu zaman aynı konunun birkaç farklı denemesiyle birlikte.

Sonraki projelerin temelindeki bellek, veri yapısı ve algoritma düşüncesi burada oturdu. Repo bu yüzden bir başlangıç noktası olarak duruyor.

## Konular

| Konu | Örnekler |
|---|---|
| **Temeller** | Koşullar, `switch` ile market alışverişi, `do while`, `continue` ve `break`, çarpım tablosu, geri sayım sayacı |
| **Algoritmalar** | Bubble, selection, insertion ve quick sort, binary search, mükemmel sayı, Floyd üçgeni |
| **Özyineleme** | Faktöriyel, Fibonacci, toplama, çarpma işlemi kullanmadan çarpım |
| **Diziler ve matrisler** | En büyük ve en küçük eleman, 2 boyutlu matris, rastgele sayı dizilerine ekleme ve silme |
| **Metinler** | Harf ve kelime sayma, en sık geçen harf, palindrom, `strcpy`, `strcat`, `strcmp`, `strncmp` |
| **Pointer'lar** | Yer değiştirme, dizi kopyalama ve birleştirme, pointer ile palindrom ve harf silme |
| **Dinamik bellek** | `malloc`, `calloc`, `realloc`, `free`, pointer'ın pointer'ı, struct ile dinamik bellek |
| **Struct, union, enum** | Otel, eczane, mağaza zinciri ve personel kayıtları, karmaşık sayılar, union ile alan hesabı |
| **Dosya işlemleri** | Satır satır ve karakter karakter okuma, öğrenci başarı tablosu, yedekleme, dosya seçme |
| **Küçük oyunlar** | Snake, Mayın Tarlası, Adam Asmaca, Taş Kağıt Makas |
| **Problem soruları** | Üçgenin türü, halıcı ücreti, konuşma ücreti, tavşan ile tavuk yarışı, vücut kitle endeksi |

## Yapı

Her klasör ayrı bir Code::Blocks projesi:

```
Konu adı/
├─ main.c           program
└─ Konu adı.cbp     Code::Blocks proje dosyası
```

## Çalıştırma

Code::Blocks ile `.cbp` dosyası açılabilir ya da herhangi bir C derleyicisiyle doğrudan derlenebilir:

```bash
gcc main.c -o program
./program
```

Snake ve Adam Asmaca Windows konsol fonksiyonlarını (`windows.h`, `conio.h`) kullandığı için Windows'ta çalışıyor.
