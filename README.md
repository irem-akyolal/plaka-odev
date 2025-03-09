# Plaka Kodu Şehir Bulma Uygulaması

Bu C uygulaması, kullanıcının girdiği plaka koduna karşılık gelen şehri ve bu şehrin hangi coğrafi bölgede olduğunu bulur.

## Gereksinimler

* Bir C derleyicisi (örneğin, GCC)
* "plaka.txt" adlı bir metin dosyası (aşağıdaki kurulum bölümüne bakın)

## Kurulum

1.  **plaka.txt Dosyası Oluşturma:**

    * Uygulamanın doğru çalışması için, her satırda bir şehrin adının bulunduğu "plaka.txt" adlı bir metin dosyası oluşturmanız gerekmektedir. Dosyadaki satır numaraları, plaka kodlarına karşılık gelmelidir. Örneğin, 1. satır "Adana", 2. satır "Adıyaman" vb. olmalıdır.
    * Dosyayı, uygulamanın C kodunda belirtilen konuma ("C:\\Users\\irem\\Documents\\C Projelerim\\plaka.txt") veya istediğiniz başka bir konuma kaydedin. Eğer farklı bir konuma kaydederseniz, C kodundaki dosya yolunu güncellemeniz gerekecektir.
2.  **Derleme:**

    * Uygulamayı derlemek için, bir C derleyicisini kullanarak aşağıdaki komutu çalıştırın:
        ```bash
        gcc plaka_bul.c -o plaka_bul
        ```
    * Burada "plaka_bul.c" sizin C kodunuzun dosya adıdır. "plaka_bul" ise oluşturulacak çalıştırılabilir dosyanın adıdır.
3.  **Çalıştırma:**

    * Uygulamayı çalıştırmak için, terminalde aşağıdaki komutu çalıştırın:
        ```bash
        ./plaka_bul
        ```

## Kullanım

1.  Uygulama başlatıldığında, sizden bir plaka kodu girmeniz istenecektir.
2.  Geçerli bir plaka kodu girdiğinizde, uygulama bu koda karşılık gelen şehri ve bu şehrin Doğu Karadeniz Bölgesi'nde olup olmadığını ekrana yazdıracaktır.
3.  Geçersiz bir plaka kodu girdiğinizde, uygulama "Hatalı kod girdiniz." mesajını verecektir.

## Örnekler
