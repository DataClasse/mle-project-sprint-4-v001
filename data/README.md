# Входные данные

Эта директория содержит исходные данные для построения системы рекомендаций.

**Файлы:**
- `tracks.parquet` - информация о музыкальных треках (идентификаторы альбомов, исполнителей, жанров)
- `catalog_names.parquet` - справочник названий треков, альбомов, исполнителей и жанров
- `interactions.parquet` - история взаимодействий пользователей с треками

**Загрузка данных:**

Если данные отсутствуют, загрузите их:

```bash
wget https://storage.yandexcloud.net/mle-data/ym/tracks.parquet -P data
wget https://storage.yandexcloud.net/mle-data/ym/catalog_names.parquet -P data
wget https://storage.yandexcloud.net/mle-data/ym/interactions.parquet -P data
```

**Примечание:** Файлы данных не включены в репозиторий из-за большого размера.

