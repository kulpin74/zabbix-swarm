# Monitoring Docker swarm from Zabbix

Monitoring with Docker API, no external scripts need. Use `{HOST.DNS}` for connect to Docker API.

I'm use SSL client certificate to connect to Docker API. You must specify filename of the certificate in `{$CERT_FNAME}` macro and filename of the key in `{$KEY_FNAME}`. Certificate and key must be in location for SSL client certificate (see SSLCertLocation in zabbix_server.conf).
