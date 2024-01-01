# sogo-dark-red
Dark red theme for SOGo web mail client used in mailcow dockerized

Created by mailcow official documentation - https://docs.mailcow.email/manual-guides/SOGo/u_e-sogo/#apply-custom-sogo-theme

## How to install
``` bash
cd /opt/mailcow-dockerized/data/conf/sogo/
wget https://raw.githubusercontent.com/NlightN22/sogo-dark-red/main/custom-theme.css
cd /opt/mailcow-dockerized/ && docker compose restart memcached-mailcow sogo-mailcow
```
Restart your browser and clear the cache `CTRL+F5`

## Example
![Main View](./examples/Screenshot 2024-01-01 152817.png)
![Preferences](./examples/Screenshot 2024-01-01 152828.png)
![Dialog window](./examples/Screenshot 2024-01-01 152916.png)
![Calendar](./examples/Screenshot 2024-01-01 152954.png)
![Date picker](./examples/Screenshot 2024-01-01 153012.png)
