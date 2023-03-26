# rocketchatyml
This is a working yml file using Traefik, Mongo and Rocket 6
s minimum, you will need:

1- A domain name
2- An email address
3- Firewall open to ports 80 and 443 (port 8080 is for the Traefik Dashboard, and should be allowed only internally, or at least from trusted IP addresses)

Just replace INSERT_DOMAIN_HERE with your domain and INSERT_EMAIL_HERE with your email.
Respect the quote marks, if they are on the yml file, leave them, if they are not, then dont add them. 

There is a setting for using a test SSL from lets encrypt, 
I recommend you use this at the beginning and intent to launch, delete, launch delete, etc. 
Because if you use Production SSL (the default on this yml file) lets-encrypt might throttle you and stop issuing SSLs.
