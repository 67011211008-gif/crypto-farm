# Crypto Farm

เกมฟาร์มจำลอง ปลูก เก็บเกี่ยว แปรรูปสินค้า และเชื่อมต่อ MetaMask กับ BNB Smart Chain Testnet

## เล่นเกม
เปิดไฟล์ `index.html` ในเบราว์เซอร์ที่ติดตั้ง MetaMask

หากเล่นผ่าน GitHub Pages ให้เปิดลิงก์ที่ตั้งค่าไว้ใน repo settings (Settings > Pages)

## ฟีเจอร์
- ปลูก รดน้ำ เก็บเกี่ยว 6 ชนิดพืช
- แปรรูปสินค้าด้วยเครื่องจักร (เตาอบ เครื่องคั้นน้ำ เครื่องทำแยม)
- ระบบ NPC และสัตว์เลี้ยงในฟาร์ม
- ระบบเลเวลและ XP
- เชื่อมต่อกระเป๋า MetaMask (BNB Smart Chain Testnet)

## Smart Contract
`contracts/FarmCoin.sol` คือเหรียญ FARM (ERC-20 แบบย่อ) ที่ deploy บน BNB Smart Chain Testnet ผ่าน Remix เจ้าของ contract เป็นคนเดียวที่เรียก `mint` ได้

หมายเหตุ: ตัวเกมในเวอร์ชันนี้ใช้ BNB จำลองในเกม ยังไม่ได้เรียก contract โดยตรง
