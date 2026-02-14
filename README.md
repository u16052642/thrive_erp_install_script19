# thrive\_erp\_install\_script19



This script is based on the install script from André Schenkels (https://github.com/aschenkels-ictstudio/openerp-install-scripts) but goes a bit further and has been improved. This script will also give you the ability to define an xmlrpc\_port in the .conf file that is generated under /etc/ This script can be safely used in a multi-ThriveERP code base server because the default ThriveERP port is changed BEFORE the ThriveERP is started.
Installing Nginx

If you set the parameter INSTALL\_NGINX to True you should also configure workers. Without workers you will probably get connection loss issues. Look at the deployment guide from ThriveERP on how to configure workers.
Installation procedureThrivw

1. Download the script:

sudo wget https://raw.githubusercontent.com/u16052642/thrive\_erp\_install\_script19/refs/heads/main/thrive\_install\_1961.sh

sudo chmod +x thrive\_install\_1961.sh

sudo ./thrive\_install\_1961.sh

