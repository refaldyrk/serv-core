# SERV
Serv Adalah Web Application Untuk Memonitoring Server Kamu Secara Realtime Dan Mudah

## Tech Stack
- Backend
    - Golang
    - JSON (Data Store)
- Frontend
  - Vite
  - Vue
  - Tailwind
## Gimana Cara Pakainya?
### Server
1. Clone Repository Ini
    ```shell
   git clone https://github.com/refaldyrk/serv-core.git
2. Konfigurasi File `docker-compose.yaml` (Opsional)
3. Setting .env
4. Jalankan `docker compose up -d` 

Ini Akan Menjalankan Serv Server dan Serv Dashboard Sekaligus <br>
Buka Address `http://localhost:3298` (Port Default)

### Client
1. Clone Repository Ini
    ```shell
   git clone https://github.com/refaldyrk/serv-core.git
2. Jalankan binary application sesuai OS kamu di folder dist
3. Lalu register url serv server, ex: (http://localhost:9090)
    ```shell
   serv reg http://locahost:9090
4. Lalu connect an client mu ke serv server dengan key (Hubungi administrator serv server)
    ```shell
   serv conn <key>
5. Lalu jalankan serv
    ```shell
   serv run

Daftarkan Serv Client di Background App

## Cara Dapatkan Key
Saat anda menjalankan `docker compose up -d` anda cetak log maka akan anda dapat key nya disana

![img.png](image/img.png)