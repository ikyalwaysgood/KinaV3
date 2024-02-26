<p align="center">
<img src="https://btch.pages.dev/file/9e4162d4034241953fdfb.jpg" alt="BOT WHATSAPP" width="400"/>


## <img height="40" src="https://raw.githubusercontent.com/innng/innng/master/assets/kyubey.gif"/> Kιɳα Bσƚ | Iky𝖔𝖋𝖋𝖎𝖈𝖎𝖆𝖑ཽ
## Highlights

- [✓] Easy to maintenance
- [✓] Support Multi-Device Connection
- [✓] Simple Base
- [✓] Connect with Pairing-Code
- [✓] Ai Features

### EXAMPLE INSTALL & RUN

install
```bash
npm install
```
RUN
```bash
npm start
```
use pairing code
```bash
node system/index.js --pairing
```

#### If npm install failed, try using yarn instead of npm
```bah
yarn
```
---------

## example plugins 
```js
export default {
  name: "", // plugins name, tampilkan menu, support array
  command: [""],
  tags: [""], // tags, tags plugins untuk menu// commad unutuk plugins
  use: "", // Ini Buat Example,
  run: async (m, { conn, usedPrefix, command }) => { // panggil saja apa yang kamu butuhkan
    // code kamu di sini 
  },
  owner: false, // ubah true Jika khusus owner,
  group: false, // ubah true jika Khusus group,
  private: false, // ubah true jika khusus private chat
  admin: false, // ubah true jika khusus admin
  botAdmin: false, // ubah true jika bot harus admin
  bot: false, // // ubah true jika khusus bot
  premium: false, // ubah true jika khusus premium 
}
```
---------
