# Deploy Web Apps Framework Next.js ke AWS

## 1. Pastikan Web Apps Berjalan di Local

- Install dependensi: `npm install`
- Buat database
- Jalankan web apps: `npm run dev`
- Akses web apps di browser `http://localhost:3000`

![alt text](image.png)

- Testing Frontend — pastikan tampilan muncul dan tanpa error
- Testing Backend `http://localhost:3000/admin`
  ```
  Username : admin
  Password : admin123
  ```

![alt text](image-1.png)
![alt text](image-6.png)

- Buat static file: `npm run build`

![alt text](image-2.png)

- Archive folder Standalone: `zip -r standalone.zip .next/standalone`

![alt text](image-3.png)

---

## 2. Proses Deploy File ke AWS EC2

- Nyalakan instance AWS
- Connect via Terminal (SSH)
- Connect FileZilla

![alt text](image-4.png)

- Upload file `standalone.zip` beserta file HTML ke EC2

![alt text](image-5.png)