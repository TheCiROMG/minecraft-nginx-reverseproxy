# Small reverse proxy for Nginx v1.15 and above

It is a reverse proxy in stream and server mode that runs incoming connections from the IP of a server to the MASTER HOST of your game server

## Requirements

1) Nginx 1.15

2) Open ports

3) Compatible system with or without firewall running an Nginx compatible system

3.a) Do not use systems that are not supported, for compatibility reasons you can only use old versions and that will not work

3.b) Ubuntu 20.04 or higher is recommended (Or a lightweight Linux system compatible with Nginx 1.15 and higher)

## ATTENTION

Depending on the system used and the version of NGINX installed, it is possible that the configuration files are not in their respective place mentioned in Git, so you will have to look for how to change the respective reading path of the file to your taste or use the one that comes by default in your respective installation (THE ROUTE DOES NOT CHANGE ANYTHING ABOUT ITS FUNCTIONALITY)

## How to use

1) Modify/rewrite the nginx.conf configuration of the root folder located in /etc/nginx
(Configure on demand)

2) Restart the service with “systemctl restart nginx” or the respective system command

3) Look for errors in the configuration and repeat point 2

4) Try pinging and searching for the server of the corresponding game

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
