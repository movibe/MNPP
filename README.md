#MNPP  Mac + Nginx + Percona + PHP
###A high performance web server in a one-click installer.

## Contributors
**This project is currently maintained by the following people:**    

[Jair Gaxiola](https://github.com/jyr) (Core developer)    
[César Salazar](http://cesarsalazar.mx/)    
[Astrata Software](http://astrata.mx)

##Features

* Start / stop services global
* Start / stop services individually
* Open the default page MNPP
* Set preferences - start  / stop global services

##Arch

* x86_64

##Runs from console

Start    
<pre><code>$ sudo mnpp --start</code></pre>
Start only one service    
<pre><code>$ sudo mnpp --start [service]</code></pre>

service: nginx | percona | php

Stop    
<pre><code>$ sudo mnpp --stop</code></pre>
Stop only one service    
<pre><code>$ sudo mnpp --stop [service]</code></pre>

service: nginx | percona | php