# shimboot-enrollment-bypass
Temporarily bypass enterprise enrollment in developer mode 

`echo --enterprise-enable-state-determination=never >/tmp/chrome_dev.conf`

`sudo mount --bind /tmp/chrome_dev.conf /etc/chrome_dev.conf`

`sudo /sbin/initctl restart ui`
