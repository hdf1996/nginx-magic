This repo holds some of my tipical scripts to configure nginx servers.
They are Apache/[insert-your-http-server-here] agnostic, so you only must use it with the port that the server currently use. Always try that it doesn't is 80 or 443.

Just paste it in your sites-available folder & then symbolic link it from sites-enabled.

Oh, one more thing! I assume in the scripts that you have configured your dns for your domain, i will never hardcode ip or domains in the scripts. 

Have fun doing magic!
- Hugo