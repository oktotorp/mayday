
<p>Hello látogató</p>
<p>Magyar nyelven tervezem az itteni projektemet elkészíteni. Aki véletlen ide talál azt üdvözlöm!</P>

<h3>C</h3>

<h3>Bash</h3>
CTRL+ALT+T<br>
echo $SHELL<br>
chmod +x or 755 file name

<pre>!#/bin/bash</pre>

<h3>Linux</h3>
<h4>iptables<h4>
<p>
-A utolso<br>
-I elso<br>
-s kit<br>
-j mit<br>
-p port<br>
#kitiltani valakit<br>
iptables -A INPUT -s 192.168.1.1 -j DROP<br>
#az egesz halozatot tiltani, hogy ne tudjanak emailt kuldeni<br>
iptables -A INPUT -s 192.168.1.1/24 -p tcp --destination-port 25 -j DROP<br>
#engedelyezni ezt mindeg az elso helyre rakjuk<br>
iptables -I INPUT -s 192.168.1.1 -j ACCEPT<br>
#torles<br>
iptables -D INPUT 3<br>
</p>


