# Docker Container Çalıştırma

## Amaç

Resmi Nginx image'ını kullanarak bir Docker container'ını çalıştırmayı öğrenmek.

## Kullanılan Komutlar

```bash
docker run -d -p 8080:80 --name nginx-container nginx
docker ps
docker stop nginx-container
docker rm nginx-container
```

## Öğrendiklerim

- Docker Hub'dan image indirme
- Docker container oluşturma ve çalıştırma
- Çalışan container'ları görüntüleme
- Container durdurma
- Container silme
- Port yönlendirme (Port Mapping)
