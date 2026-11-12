# MacOS Tahoe X Cursor

macOS Tahoe görünümünden ilham alan, Linux masaüstü ortamları için hazırlanmış
Xcursor teması.

Tema KDE Plasma, GNOME ve Xcursor destekleyen diğer masaüstü ortamlarında
kullanılabilir.

## Kurulum

### Grafik arayüzüyle

1. Bu repository'yi indirin ve arşivden çıkarın.
2. Tema klasörünü `~/.icons/` veya `~/.local/share/icons/` içine kopyalayın.
3. Sistem ayarlarından **Fare ve Dokunmatik Yüzey → İmleç Teması** bölümünü açın.
4. **MacOS-TahoeX-Cursor** temasını seçip uygulayın.

### Terminal ile

```bash
mkdir -p ~/.icons
cp -r MacOS-TahoeX-Cursor ~/.icons/
```

KDE Plasma kullanıyorsanız temayı doğrudan uygulayabilirsiniz:

```bash
plasma-apply-cursortheme MacOS-TahoeX-Cursor
```

Tema listede görünmüyorsa KDE simge önbelleğini yenileyin ve ayarlar
uygulamasını yeniden açın:

```bash
kbuildsycoca6 --noincremental
```

## Tema yapısı

```text
MacOS-TahoeX-Cursor/
├── cursors/       # Xcursor dosyaları
├── index.theme    # Tema bilgileri
└── README.md
```

## Notlar

- Bu paket Linux/Xcursor formatındadır; Windows `.cur` veya `.ani` dosyası
  içermez.
- Bazı uygulamalar eski imleci önbelleğe alabilir. Böyle bir durumda
  uygulamayı kapatıp yeniden açın.
- Değişikliklerin tüm uygulamalarda görünmesi için oturumu kapatıp açmanız
  gerekebilir.

## Lisans

Bu repository, kullanılan cursor görsellerinin lisansını değiştirmez.
Görsellerin kullanım koşulları için orijinal tasarımcıların ve kaynak
projenin lisans bilgilerini kontrol edin.
