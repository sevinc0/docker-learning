# Docker Volume Kullanımı

## Amaç

Host (ana makine) ile Docker container arasında dosya paylaşımını sağlamak ve verilerin kalıcı olmasını öğrenmek.

## Kullanılan Komutlar

```bash
docker run -d -p 8081:80 \
-v $(pwd)/html:/usr/share/nginx/html nginx
```

## Öğrendiklerim

- **Bind Mount** kullanarak host bilgisayardaki bir klasörü container'a bağlamayı
- **Docker Volume** kavramını ve kullanım amacını
- Verilerin container silinse bile korunmasını (Data Persistence)
- Host üzerinde yapılan dosya değişikliklerinin container içinde de anında görülebilmesini
