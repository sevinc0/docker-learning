# Docker Network Kullanımı

## Amaç

Docker container'larının aynı ağ üzerinde birbirleriyle iletişim kurmasını öğrenmek.

## Kullanılan Komutlar

```bash
docker network create demo-network
docker network inspect demo-network
```

## Öğrendiklerim

- **Docker Bridge Network** yapısını ve çalışma mantığını
- Container'ların aynı ağ üzerinden birbirleriyle iletişim kurmasını
- **DNS Resolution** sayesinde container isimleriyle birbirlerine erişebilmelerini
- `docker network inspect` komutu ile ağın yapılandırmasını görüntülemeyi
