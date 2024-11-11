# Redis use case - guide

ตัวอย่างการ implement redis 4 use case
1. Session (app.js)
2. Register + Queue (queue.js)
3. Realtime (socket.js)
4. Publisher / Subscriber (publisher.js, subscriber.js)

สามารถ start project ได้ด้วย command

```shell
npm install
node <ชื่อไฟล์ที่ต้องการทดลอง>
```

สำหรับ redis ใน git นี้ทำการลงด้วย `docker-compose.yml` สามารถดำเนินการ run redis ด้วยคำสั่งของ docker-compose ได้เลย

```shell
docker-compose up -d --build
```