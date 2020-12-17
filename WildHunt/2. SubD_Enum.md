# Subdomain Enumeration:

**Sites:**

[`https://dnsdumpster.com/`](https://dnsdumpster.com/)

**Using amass:**

`amass enum -d [target.com](http://target.com) -ip`

**Using subfinder:**

`subfinder -d [target.com](http://target.com) -t 25 -timeout 5 -silent`

**DNS BruteForcing using massdns:**

`./bin/massdns -r lists/resolvers.txt -t AAAA domains.txt > results.txt` 

that lists/resolvers.txt file is in massdns scan installation folder.

**Using GoBuster:**

`gobuster dns -d domain[.com](http://upwork.com/) -w /usr/share/wordlists/rockyou.txt`

Note: GoBuster is more accurate and massdns might blacklist you from any server.

**Using Aquatone:**

`aquatone-discover -d target.com`

**Using altdns  by shub:**

`altdns -i subdomains.txt -o data_output -w words.txt -r -s results_output.txt`

To find the DNS pattern, use altdns.

**Passive identification and alert of new sub domains on the target.**

[`http://threatcrowd.org/searchApi/v2/domain/report/?domain=uber.com`](http://threatcrowd.org/searchApi/v2/domain/report/?domain=uber.com)

[`https://threatcrowd.org`](https://threatcrowd.or/)
