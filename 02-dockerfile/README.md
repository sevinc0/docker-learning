# Dockerfile Kullanımı

## Amaç

Dockerfile kullanarak özel bir Docker image'ı oluşturmayı öğrenmek.

## Kullanılan Dosyalar

- Dockerfile
- index.html

## Kullanılan Komutlar

```bash
docker build -t mywebsite .
docker run -d -p 8080:80 mywebsite
```

## Öğrendiklerim

- `FROM` komutu ile temel image seçmeyi
- `COPY` komutu ile dosyaları image içerisine kopyalamayı
- `EXPOSE` komutu ile uygulamanın kullanacağı portu belirtmeyi
- Docker image oluşturmayı (`docker build`)
- Oluşturulan image'dan container çalıştırmayı (`docker run`)
