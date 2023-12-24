Soru 1 Cevap :
select city, country from city
left join country on country.country_id = city.country_id; <br>
Soru 2 Cevap :
select payment_id, first_name, last_name from customer
right join payment on customer.customer_id = payment.customer_id; <br>
Soru 3 Cevap :
select rental_id, first_name, last_name from customer
full join rental on customer.customer_id = rental.customer_id;
