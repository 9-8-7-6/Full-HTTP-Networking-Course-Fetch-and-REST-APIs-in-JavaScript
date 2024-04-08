# Full-HTTP-Networking-Course-Fetch-and-REST-APIs-in-JavaScript

HTTP是網路溝通的protocol，protocol意思是溝通的協定規則
Http可以把1和0解析(parse)成我們需要的資訊
Http的核心就是request(請求)和respond(回應)的系統
使用的fetch是一種內建的函示，fetch要先await來暫停，直到得到response(Json型態)，Json是JavaScript Object Notation，而且需要把Json parse成JavaScript Object，用法會是response.json()
IPv4位址是四個數組成，每個數由0到255組成 ，之間由句點隔開，例如255.255.255.255，需要利用到DNS(Domain Name System)，功能是讓網域名成轉換成IP，例如google.com就是網域名
所以當我們需要http request，會經過兩個步驟，會先透過DNS來把域名resolve(解析)成ip，使用ip address到server
如果response是SyntaxError…doctype…，很可能因為response是html
JavaScript有URL這個function可以把url解析成需要的部分，例如Protocol和Hostname, Port等等，舉例來說const Url_Output = new URL('https://example.com/path?query=string')
Http的默認端口是80，Tttps的是443，也可以透過指定端口
URL只需要有Protocol和Domain即是valid
