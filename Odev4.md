- Film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
```
SELECT DISTINCT replacement_cost from film;
```

- Film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
```
SELECT DISTINCT replacement_cost from film;
```
- Film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
```
SELECT COUNT (*) from film
WHERE title LIKE 'T%' AND rating = 'G';
```
- Country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
```
SELECT COUNT (*) from country
WHERE country LIKE '_____'
```
- City tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
```
SELECT COUNT (*) from city
WHERE city ILIKE '%r'
```