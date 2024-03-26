# tmp
temp repository for DAPS

<p><code>sudo hping3 --icmp --flood -c 500 127.0.0.1</p>


<p><code>sudo service ssh start</code></p><p><code>sudo hydra -l root -P /usr/share/wordlists/metasplpoit/unix_passwords.txt ip_address ssh -t 4 -V</code></p>


<p><code>openssl req -x509 -newkey rsa:4096 -nodes -out cert.pem -keyout key.pem -days 365</code></p>



<p><code>sudo tshark -i lo -Y "(udp || tcp.flags.syn == 1 || icmp)" -T fields -e frame.time_epoch -e ip.src -e frame.len -e _ws.col.Protocol -e _ws.col.Info -E header=y -E separator=, -E quote=d -E occurrence=f > ~/Desktop/project/tcpdump_output.txt</code></p><p><code>sudo hping3 --udp --flood --rand-source --destport 24 -c 500 127.0.0.1</code></p>
