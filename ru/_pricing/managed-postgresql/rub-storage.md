{% include [local-ssd для Ice Lake только по запросу](../../_includes/ice-lake-local-ssd-note.md) %}

| Услуга                                  | Цена за ГБ в месяц                                                  |
|-----------------------------------------|---------------------------------------------------------------------|
| Стандартное сетевое хранилище           | {{ sku|RUB|mdb.cluster.network-hdd.pg|month|string }}               |
| Нереплицируемое сетевое хранилище       | {{ sku|RUB|mdb.cluster.network-ssd-nonreplicated.pg|month|string }} |
| Быстрое сетевое хранилище               | {{ sku|RUB|mdb.cluster.network-nvme.pg|month|string }}              |
| Быстрое локальное хранилище             | {{ sku|RUB|mdb.cluster.local-nvme.pg|month|string }}                |
| Резервные копии сверх размера хранилища | 2,5424 ₽                                                            |
