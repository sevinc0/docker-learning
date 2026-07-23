# Docker Compose Kullanımı

## Amaç

Birden fazla Docker servisini **docker-compose.yml** dosyası kullanarak tek komutla çalıştırmayı ve yönetmeyi öğrenmek.

## Kullanılan Dosyalar

- docker-compose.yml
- index.html

## Kullanılan Komutlar

```bash
docker compose up -d
docker compose down
```

## Öğrendiklerim

- **Docker Compose** kullanarak birden fazla container'ı yönetmeyi
- Çoklu container uygulamalarını (Multi-container Applications) tek komutla başlatmayı ve durdurmayı
- **Volume Mapping** ile verileri paylaşmayı ve kalıcı hale getirmeyi
- `docker compose up -d` komutu ile servisleri arka planda çalıştırmayı
- `docker compose down` komutu ile servisleri durdurup kaldırmayı
