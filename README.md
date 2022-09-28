# Cat Api

#### Дан масив состоящий из элементов с данными объявления.

```
$adverts = [
    ['rooms' => 5, 'category' => 'sale', 'price' => 55000000, 'type' => 'dom'],
    ['rooms' => 2, 'category' => 'sale', 'price' => 21500000, 'type' => 'kvartira'],
    ['rooms' => 2, 'category' => 'rent', 'price' => 200000, 'type' => 'kvartira', 'period' => 'month'],
    ['rooms' => 1, 'category' => 'rent', 'price' => 15000, 'type' => 'kvartira', 'period' => 'day'],
];
```

Требования:

Из элементов предоставленного массива нужно создать объекты c классом Advert,
в котором должен быть метод getTitle(), который выводит заголовок (указанный в примере) объявления в зависимости от параметров.
И необходимо вывести в цикле заголовки всех объявлений массива.

Пример вывода заголовка объявления:
 - Продам 5-комнатный дом за 55 млн. тг
 - Продам 2-комнатную квартиру за 21.5 млн. тг
 - Сдам 2-комнатную квартиру за 200 000 тг в месяц
 - Сдам 1-комнатную квартиру за 150 000 тг в сутки

