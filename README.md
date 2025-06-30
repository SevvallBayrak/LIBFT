# libft - Kendi C Standart Kütüphanem

Bu proje, C dilindeki temel standart kütüphane fonksiyonlarını **sıfırdan yazmayı** ve **hafıza yönetimi** ile **string işlemleri** konularında derinlemesine bilgi sahibi olmayı amaçlar. `libft.a` adlı statik bir kütüphane oluşturulmuştur ve bu kütüphane farklı C projelerinde **yeniden kullanılabilir** yapıdadır.

---

## Proje Hakkında

Bu kütüphane, C standart kütüphanesindeki (libc) birçok temel fonksiyonun kendi implementasyonları ile oluşturulmuştur.

Fonksiyonlar:
- `ft_strlen`, `ft_memcpy`, `ft_memset`, `ft_bzero`, `ft_atoi`, `ft_calloc`, `ft_strdup`
- `ft_strncmp`, `ft_strchr`, `ft_strrchr`, `ft_strlcpy`, `ft_strlcat`
- `ft_split`, `ft_strjoin`, `ft_substr`, `ft_itoa`, `ft_strtrim`
- ve diğer temel yardımcı fonksiyonlar

Ek olarak:
- `Makefile` ile otomatik derleme
- Modüler yapı ve `static` fonksiyon kullanımı
- Memory leak testleri yapılmıştır

---

## Neler Öğrendim?

- C dilinde **string**, **bellek** ve **karakter işlemleri**
- `malloc`, `free` gibi fonksiyonlarla **heap yönetimi**
- **Pointer aritmetiği** ve bellek adresleme
- `Makefile` ile **otomatik derleme süreçleri**
- Kod stiline uygun **temiz ve modüler** yazım
- `libft.a` adında **statik kütüphane** üretimi
- `static` fonksiyonlarla **encapsulation**
- **Norminette** gibi kod standartlarına uygunluk (42 okulu)

---

## 🛠️ Nasıl Derlenir?

```bash
make        # libft.a dosyasını oluşturur
make clean  # obje dosyalarını siler
make fclean # obje + libft.a dosyasını siler
make re     # temiz derleme
