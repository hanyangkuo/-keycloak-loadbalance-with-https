* copy from youtube-tutorial: [Keycloak Cluster - Up and Running in Seconds ](https://www.youtube.com/watch?v=P96VQkBBNxU)


* using `docker compose -f stack.yml up` to run.


# Create certificate using openssl
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout server.key -out server.crt

# Reference
https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-nginx-on-centos-7