# myblue

//Everytime I login to any network(SAIC), my IP address  changes.
I should check my IP every time by going to system preferences>sharing>remote login to get my IP address. For example, 22.22.22.222.
Inside the index file change the IP address in this part
```JavaScript
const res = await fetch(`http://22.22.22.222/answer?q=${e.target.value}&a=${t.value}`)
```
to the new IP address.
+In this particular situation when IP address always changes, it is fine to leave the IP address. But do not push to Github or upload anywhere the file with local IP address, never. (Or you could put firewall to close other ports except the very port you are using.)
