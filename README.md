# 1c-diadoc-upd-address
<p align="center">
  <img src="preview.png" alt="Адрес доставки в УПД Диадок" width="800"/>
</p>
Подстановка адреса доставки в УПД (Диадок) из документа "Реализация товаров и услуг"

Подключаемый модуль (epf) для Диадок, который автоматически подставляет **фактический адрес доставки** в поле "Грузополучатель" УПД СЧФДОП.

## Возможности
- Поддержка форматов УПД 970 (и 820 при необходимости)
- Получение адреса из раздела доставки документа "Реализация товаров и услуг"
- Работа без изменения Диадок (используется ПМ)

## Установка
1. Зайдите в Диадок → ⚙️ Расширенные настройки → Подключаемый модуль
2. Выберите способ подключения: **В справочнике 1С**
3. Добавьте обработку из файла `diadoc_address_delivery.epf`

> 💡 После подключения обязательно перезапустите окно Диадока.

## Совместимость
- Управление торговлей 11.5.12.260
- Комплексная автоматизация 2.5.21.116
- БСП 3.1.9.302

## Лицензия
Этот проект распространяется без ограничений — вы можете использовать, копировать, изменять и распространять его свободно.

⭐ Если модуль оказался полезным — можете поставьте звезду репозиторию)
