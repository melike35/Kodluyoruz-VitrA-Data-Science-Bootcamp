<h1 align="center"> Odev 9  <h1/>
  
#### city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

~~~sql
SELECT city,country FROM city INNER JOIN country ON country.country_id = city.country_id
~~~
  
  #### customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

~~~sql
SELECT payment_id,first_name,last_name FROM customer INNER JOIN payment ON customer.customer_id = payment.customer_id
~~~
  
  ####  customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

~~~sql
SELECT rental_id,first_name,last_name FROM customer INNER JOIN rental ON customer.customer_id = rental.customer_id
~~~

  <h1 align="center"><img src="https://app.patika.dev/cool-doge.gif" width="60px" /></h1>
  
