Example Data
============

If you'd like some data to test your new storefront you can populate the database with example products and orders:

.. code-block:: console

 $ python manage.py populatedb


server {
	listen 80;
	listen [::]:80;

	server_name noithatsla.com;


	location / {
		proxy_pass http://127.0.0.1:8000;
	}
}