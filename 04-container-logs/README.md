# Container Loglarını Görüntüleme

## Amaç

Docker container'larının loglarını görüntülemeyi ve olası hataları incelemeyi öğrenmek.

## Kullanılan Komutlar

```bash
docker logs mywebsite-container
docker logs -f mywebsite-container
```

## Öğrendiklerim

- `docker logs` komutu ile container loglarını görüntülemeyi
- `docker logs -f` komutu ile logları gerçek zamanlı takip etmeyi
- Loglar sayesinde hata ayıklama (Troubleshooting) yapmayı
- Çalışan uygulamanın durumunu loglar üzerinden kontrol etmeyi
