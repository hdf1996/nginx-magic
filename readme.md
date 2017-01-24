This repo holds some of my tipical scripts to configure nginx servers.
These are Apache/[insert-your-http-server-here] agnostic. Only take care that Apache/[insert-your-http-server-here] is not holding the same port that you are trying to use (tipically 80 or 443)

Just paste it in your sites-available folder & then symbolic link it from sites-enabled.

Oh, one more thing! I assume in the scripts that you have configured your dns for your domain

Have fun doing magic!
- Hugo

PS: Hey, take this Stellar squirrel that finds out there is no oxygen. Powered by [@AgussAlc](https://twitter.com/AgussAlc "@AgussAlc")
![alt tag](https://raw.githubusercontent.com/hdf1986/nginx-magic/master/squirrel.jpeg)
