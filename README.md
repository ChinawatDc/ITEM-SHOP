# ITEM GAME 🎮🕹

#### เว็ปซื้อขายเกม-ไอเทมต่างๆ
- **API** สร้างด้วย Node, GraphQL, Express, Sequelize (MySQL) และ JWT Auth
- **WebApp** สร้างด้วย React และ Redux พร้อมกับ Server Side Rendering (SSR)

## Core Structure
    code
      ├── package.json
      │
      ├── api (api.example.com)
      │   ├── public
      │   ├── src
      │   │   ├── config
      │   │   ├── migrations
      │   │   ├── modules
      │   │   ├── seeders
      │   │   ├── setup
      │   │   └── index.js
      │   │
      │   └── package.json
      │
      │
      ├── web (example.com)
      │   ├── public
      │   ├── src
      │   │   ├── modules
      │   │   ├── setup
      │   │   ├── ui
      │   │   └── index.js
      │   ├── storybook
      │   │
      │   └── package.json
      │
      ├── .gitignore
      └── README.md


## ตั้งค่าและใช้งาน
- ข้อกำหนดเบื้องต้น
  - Node
  - MySQL (or xampp / heidisql )
- โคลน `git clone https://github.com/puem2639/ITEM-Master`
- เปลี่ยนเป็น `code` `cd code`
- การกำหนดค่า
  - Modify `/api/src/config/database.json` สำหรับข้อมูลรับรองฐานข้อมูล
  - Modify `/api/.env` สำหรับ PORT
  - Modify `/web/.env` สำหรับ PORT / API URL
  - Modify `/mobile/src/setup/config.json` สำหรับ API URL (tip: ใช้ `ifconfig` เพื่อรับที่อยู่ IP address)
- ติดตั้ง
  - API: ติดตั้ง packages และ database setup `cd api` และ `npm run setup`
  - Webapp: ติดตั้ง packages `cd web` และ `npm install`
- การพัฒนา
  - Run API `cd api` และ `npm start`,เรียกดู GraphiQL ที่ http://localhost:8000/
  - Run Webapp `cd web` และ `npm start`,เรียกดู webapp ที่ http://localhost:3000/

##สมาชิก
-นายชินวัตร ดาวชัย (Code Developer Lv3)
-นายนันทภูมิ สดรัมย์ (Code Developer Lv2)
-นายฐิติกร จันตา (Code Developer Lv1)
-นายเกียรติสุรักษ์ วงศ์ชัย (Code Developer Lv1)
