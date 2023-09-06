
# Sesli Asistan ve Cleverbot ile Sohbet Uygulaması

Bu uygulama, sesli komutları tanıyabilen bir sesli asistan ile Cleverbot'u birleştiren ve kullanıcı ile yapay zeka arasında konuşma sağlayan bir Python uygulamasını göstermektedir. Ayrıca, bu uygulama, bir GIF görüntüsünü eşzamanlı olarak görüntüleyebilir ve kullanıcı ile bot arasındaki sohbeti kaydedebilir.

## Kullanılan Kütüphaneler

- `cleverbotfree`: Cleverbot ile etkileşim için kullanılan kütüphane.
- `googletrans`: Metin çevirisi için kullanılan kütüphane.
- `gtts`: Metni sesli olarak çevirmek için kullanılan kütüphane.
- `speech_recognition`: Sesli komutları tanımak için kullanılan kütüphane.
- `tkinter`: Grafiksel kullanıcı arayüzü (GUI) oluşturmak için kullanılan kütüphane.
- `PIL`: Resimlerle çalışmak için kullanılan kütüphane.
- `playsound`: Ses dosyalarını çalmak için kullanılan kütüphane.
- `threading`: Eşzamanlı işlemleri yönetmek için kullanılan kütüphane.

## Uygulama Açıklaması

Uygulama, aşağıdaki temel özelliklere sahiptir:

1. Sesli komutları tanıma: `speech_recognition` kütüphanesi kullanılarak sesli komutları algılar ve metne dönüştürür.

2. Metin çevirisi: Kullanıcının sesli komutları veya Cleverbot'un cevapları, kaynak dildeki metinden hedef dile çevrilir. Bu, `googletrans` kütüphanesi ile gerçekleştirilir.

3. Metin konuşma: Çevrilen metin, sesli olarak çevrilmek üzere `gtts` kütüphanesi kullanılarak ses dosyasına dönüştürülür ve oynatılır.

4. Cleverbot ile sohbet: Kullanıcı ve Cleverbot arasında bir sohbet oluşturulur. Kullanıcı sesli komutlarını kullanarak Cleverbot ile etkileşime geçebilir.

5. GIF görüntüsü: Eşzamanlı olarak bir GIF görüntüsü görüntülenir. Bu, `tkinter` ve `PIL` kütüphaneleri kullanılarak gerçekleştirilir.

## Nasıl Kullanılır

1. Uygulamayı çalıştırın.
2. Sesli komutları kullanarak Cleverbot ile sohbet edin. "quit" komutu ile sohbeti sonlandırabilirsiniz.
3. Eşzamanlı olarak bir GIF görüntüsü görüntülenecektir.

## Notlar

- Uygulama, Google Translate API'sini kullanmaktadır. API anahtarınızı ve yapılandırmanızı doğru bir şekilde ayarladığınızdan emin olun.
- Bu uygulama, birden fazla thread kullanılarak sesli komutları, metin çevirisini ve GIF görüntüsünü eşzamanlı olarak işler.

Umarım bu açıklama, uygulamanızı daha iyi anlamanıza ve geliştirmenize yardımcı olur. Başarılar dilerim!
