# sql-odev-6
1)film tablosunda bulunan rent_rate sütunundaki değerlerin ortalaması nedir?

SELECT AVG(rental_rate) FROM film

2)film tablosunda bulunan filmlerden kaç Tanesi 'C' karakteri ile başlar?

SELECT COUNT(rental_rate) FROM film WHERE title LIKE 'C%';

3)film tablosunda bulunan filmlerden rent_rate değeri 0.99 a eşit olan en uzun (uzunluk) film kaç dakikadır?

SELECT MAX(length) FROM film WHERE rental_rate = 0.99;

4)film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replace_cost değeri vardır?

SELECT COUNT(DISTINCT replacement_cost) FROM film WHERE length>150;

