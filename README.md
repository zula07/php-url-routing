# PHP URL Routing Örneği

Bu proje, PHP ile oluşturulmuş çok basit bir URL routing (yönlendirme) örneğidir.

## Özellikler
- `/` - Ana sayfa
- `/about` - Hakkımızda sayfası
- Tanımlanmayan yollar için 404 sayfası

## Nasıl Çalışır?
`index.php` dosyası, `$_SERVER['REQUEST_URI']` değişkenini kullanarak gelen isteği kontrol eder ve ilgili view dosyasını `require` eder.
