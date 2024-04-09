# Hava Durumu Uygulaması

Bu uygulama, kullanıcının hava durumu bilgisini almasına olanak tanır. Kullanıcı, şehir adını girerek hava durumu bilgisini alabilir.

## Kullanılan Kütüphaneler

- `tkinter`: Grafik arayüz oluşturmak için kullanılan standart bir Python kütüphanesidir.
- `PIL`: Python Imaging Library, resim işleme işlevleri sağlar.
- `requests`: HTTP istekleri göndermek için kullanılan bir Python kütüphanesidir.

## API Bilgileri

Hava durumu bilgileri, OpenWeatherMap API'si kullanılarak alınmaktadır. API anahtarınızı `api_key` değişkenine atamanız gerekmektedir.

## Fonksiyonlar

- `getWeather(city)`: Belirli bir şehir için hava durumu bilgisini getiren fonksiyon.
- `main()`: Kullanıcının girdiği şehir adına göre hava durumu bilgisini alarak arayüzde gösteren fonksiyon.

## Kullanım

1. Uygulamayı başlatın.
2. Arama kutusuna hava durumu bilgisini almak istediğiniz şehrin adını girin.
3. "Arama" butonuna tıklayarak hava durumu bilgisini görüntüleyin.

## Notlar

- `cityEntry` alanına şehir adını girerken Türkçe karakterler kullanabilirsiniz.
- Hava durumu bilgisi başarıyla alındığında, ilgili şehir adı, sıcaklık, durum ve ikon arayüzde görüntülenecektir.



