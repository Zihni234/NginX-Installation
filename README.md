# NginX-Installation

# Apa itu NginX?
NGINX (dibaca engine-ex) adalah software web server open-source yang berfungsi sebagai reverse proxy, penyeimbang beban HTTP, serta proxy email untuk IMAP, POP3, dan SMTP. layanan NGINX sudah banyak digunakan oleh website dengan traffic yang tinggi. Beberapa yang menggunakannya adalah Google, Netflix, Adobe, Cloudflare, WordPress.com, dan masih banyak lagi.
# Tahap singkat penginstalan
- Pertama kita harus meng-update ubuntu server itu sendiri dengan command sudo apt update
- setelah itu barulah kita bisa mulai instalasi NginX dengan command sudo apt install nginx
- Beri izin untuk berjalan pada Nginx HTTP dengan command sudo ufw allow 'Nginx HTTP'
- Aktifkan Nginx dengan command systemctl start nginx
- masukkan command curl -4 icanhazip.com dan cek ip dengan command ifconfig
- lalu masukkan IP pada web pencarian dan lihat apakah NginX berhasil terinstall atau tidak
- Jika berhasil, akan ada laman default NginX bertuliskan "Welcome to nginx!"
