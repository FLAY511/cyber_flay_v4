# CYBER FLAY TOOLS v4

**OSINT (15 fitur)** + **Deface (HTML+JS)** + **Menu Lain (10 fitur)** — dibuat untuk Termux (Bash).  
Gunakan hanya pada aset milik sendiri atau dengan izin tertulis (responsible disclosure).

## 📥 Install di Termux
```bash
pkg update && pkg upgrade -y
pkg install git curl jq bc openssl wget -y
pkg install dnsutils traceroute whois netcat-openbsd -y   # untuk fitur OSINT
git clone https://github.com/FLAY511/cyber_flay_v4.git
cd cyber_flay_v4
chmod +x flay_hacker_v4.sh
```

## ▶️ Jalankan
```bash
./flay_hacker_v4.sh
```

## 🕵️ OSINT (15)
1. WHOIS Lookup (cli + RDAP)
2. GeoIP Lookup (ip-api)
3. DNS Lookup (A/MX/NS)
4. Reverse DNS (PTR)
5. Subdomain Finder (crt.sh)
6. HTTP Headers
7. HTTP Status Code
8. Traceroute
9. Ping
10. Port Scan (nc)
11. SSL Certificate Info (openssl)
12. Reverse IP → Domains (hackertarget)
13. Email Breach Check (HIBP, butuh API key: env `HIBP_KEY`)
14. GitHub User OSINT (api.github.com)
15. Username Check (GitHub/GitLab/Reddit)

## 🛠️ Menu Lain (10)
1. Cek IP Publik
2. Cek Cuaca (wttr.in)
3. Kalkulator (bc)
4. Tanggal & Jam
5. Speedtest sederhana (wget 10MB)
6. Base64 Encode
7. Base64 Decode
8. Hash Generator (MD5/SHA1/SHA256)
9. URL Shortener (tinyurl)
10. QR Code Generator (api.qrserver.com)

## ⚠️ Catatan
- Beberapa endpoint gratis memiliki rate-limit; bila gagal, coba lagi nanti.
- Untuk HIBP, siapkan API key lalu export:
  ```bash
  export HIBP_KEY=KEY_KAMU
  ```

## 👤 Author
Dibuat oleh **CYBER FLAY** (white-hat).
