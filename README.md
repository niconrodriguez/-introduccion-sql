# -introduccion-sql

1) ¿Cuántas tiendas (store) hay en total?

   SELECT count(*) FROM store

2) ¿Cuántas películas (film) tienen una duración de más de 120 minutos?
  SELECT count (*)
  FROM film
  WHERE length > 120
   
3) ¿Cuántos pagos realizó el cliente (customer) con el ID 472?

   SELECT count (*)
   FROM payment
   WHERE customer_id = 472

4) ¿Cuál es el ID de la película (film) que tiene un ID de inventario (inventory) 303?

  SELECT film_id
  FROM inventory
  WHERE inventory_id = 303

5) ¿Cuál es la dirección (address) y distrito (district) de la persona cuyo teléfono es 634445428822?

SELECT address,district 
FROM address 
WHERE phone= '634445428822'
