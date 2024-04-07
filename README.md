# Hava Durumu Ogrenme

# Hava Durumu API Kullanımı

Bu Python betiği, OpenWeatherMap API'sini kullanarak kullanıcıdan bir şehir adı alır ve o şehrin güncel hava durumu bilgilerini görüntüler.

## Gereksinimler

- Python 3.x
- requests kütüphanesi (kurmak için: `pip install requests`)
- Bir OpenWeatherMap API anahtarı (ücretsiz olarak [buradan](https://openweathermap.org) alınabilir)

## Kullanım

1. Öncelikle, OpenWeatherMap sitesine gidin ve bir API anahtarı alın.
2. Anahtarı `config.py` dosyasına ekleyin:

    ```python
    API_KEY = "YOUR_API_KEY"
    ```

3. Ardından, `hava_durumu.py` dosyasını çalıştırarak betiği başlatın. Betik sizi bir şehir adı girmeniz için bir giriş bekleyecektir.
4. Şehir adını girdikten sonra, betik API'ye bağlanacak ve o şehre ait güncel hava durumu bilgilerini görüntüleyecektir.



