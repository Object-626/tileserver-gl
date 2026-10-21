# Изменения зависимостей

Форк `Object-626/tileserver-gl`, ветка `leaflet-removed`
База: upstream `5d74c80` (08.09.26) → `fb04dfa` (30.09.26)

## Повышены

```
tar                     6.2.1, 7.5.11  ->  7.5.22
shell-quote             1.8.4          ->  1.10.0
body-parser             2.2.1          ->  2.3.0
@tootallnate/once       1.1.2          ->  2.0.1
sharp                   0.35.3         ->  0.35.4
morgan                  1.11.0         ->  1.12.1
brace-expansion         1.1.18, 5.0.9  ->  1.1.21, 5.0.12
ip-address              10.5.0         ->  10.7.2
fast-uri                3.1.6          ->  3.1.8
content-type            1.0.5          ->  2.1.0
type-is                 2.0.1          ->  2.1.0
iconv-lite              0.7.0          ->  0.7.3
minipass                5.0.0          ->  7.1.3
@emnapi/runtime         1.11.1         ->  1.11.3
@img/sharp-*            0.35.3         ->  0.35.4
@img/sharp-libvips-*    1.3.2          ->  1.3.3
```

## Удалены

```
leaflet                 1.9.4
leaflet-hash            0.2.1
```

## Осталось открытым

```
maplibre-gl             5.24.0   ->  6.11.2   critical
handlebars              4.7.9    ->  4.7.10   critical
proxy-addr              2.0.7    ->  2.0.8    critical
shell-quote             1.10.0   ->  1.12.0   critical
sharp                   0.35.4   ->  0.35.5   high
http-cache-semantics    4.1.1    ->  —        high
```

Все закрыты в `upstream/master` (`2264416`, 13.10.26). Нужен мерж.
