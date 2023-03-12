# openmusic-queue-consumer

Repository aplikasi tambahan pada Submission Kelas [Dicoding Belajar Fundamental Aplikasi Back-End](https://www.dicoding.com/academies/271) 
untuk memenuhi kriteria "fitur Expor Lagu Pada Playlist" menggunakan message broker RabbitMQ.

Silahkan bila tertarik untuk menjadikan repository ini sebagai refrensi 🙂

Submission Open Music API : https://github.com/HendP/openmusic-app-back-end

# Quickstart

Clone Repository
```
git clone https://github.com/HendP/openmusic-queue-consumer.git
```

Masuk kedalam folder proyek
```bash
cd openmusic-queue-consumer
```

Install library
```bash
npm || yarn install
```

Menyiapkan environment dengan menggunakan .env.template yang tersedia
```bash
# Postgresql
PGUSER=
PGHOST=
PGPASSWORD=
PGDATABASE=
PGPORT=

# Nodemailer SMTP authentication
MAIL_HOST=
MAIL_PORT=
MAIL_ADDRESS=
MAIL_PASSWORD=

# Message broker
RABBITMQ_SERVER=
```

Jalankan proyek consumer ini
```bash
npm run start || yarn start
```
