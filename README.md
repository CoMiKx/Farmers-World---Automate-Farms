# Farmers-World-Automate-Mining&Farms
Farmers World - Automate-Mining&amp;Farms
แจก Userscript Automate Mining ครับ
เหมาะสำหรับคนที่มีคอมสำหรับรันบอท 24/7
รองรับการใช้ Stored Mining จาก Membership ทุกชนิด
ในตอนนี้รองรับแค่ Mining, Farm เท่านั้นนะครับ
ไม่รองรับการใช้งานกับ Animal และอื่น ๆ
(เนื่องจากผมไม่มีเครื่องมือสำหรับสายอื่นนอกจาก Mining และ Farms)

มีคุณสมบัติต่อไปนี้ครับ
  - เข้าสู่ระบบ Wax Cloud Wallet อัตโนมัติ เมื่อเข้าเว็บเกม
  - กด Mine ให้กับพวก Tools อัตโนมัติเมื่อถึงเวลา
  - กด Water อัตโนมัติให้ระบบฟาร์มอัตโนมัติเมื่อถึงเวลา
  - กด Claim ให้กับพวก Memberships อัตโนมัติเมื่อถึงเวลา
  - (ทางเลือก) กด Mine แบบรอใช้ Stored Mining
    โดยหากเปิดใช้งาน บอทจะรอจนกว่าครบโควต้าที่เก็บได้
    แล้วกด Mine ทีเดียว ทำให้ประหยัดการใช้ CPU Wax เล็กน้อย
  - เติม Energy ให้เต็มโดยอัตโนมัติ เมื่อ Energy ไม่เพียงพอ
    สำหรับการ Mine (Tools) / Claim (Memberships) / Water (Farms plot)
  - ซ่อม Durability ของ Tools ให้เต็มโดยอัตโนมัติ
    เมื่อ Durability ไม่เพียงพอสำหรับการ Mine
  - ปิดหน้าต่างที่เกิดขึ้นจากการทำงานของบอทให้อัตโนมัติ
    รวมไปถึงหน้าต่าง Error และ CPU Wax เต็ม (ที่เกิดจากบัค)
    หาก CPU Wax เต็ม บอทจะพยายามกระทำใหม่จนกว่าจะสำเร็จ
    
บอทตัวนี้ไม่ได้มีอะไรให้ตั้งค่ามากมาย มีแค่ 2-3 อย่างครับ
  - window.automateEnable = true;
  - window.storedMiningEnable = false;
  - window.interval = 5000;
automateEnable = เปิด/ปิด การทำงานของบอท (ใช้ true/false)

storedMiningEnable = เปิด/ปิดการทำงาน Stored Mining (ใช้ true/false)

interval = ระยะเวลาความถี่ที่บอทจะเช็คความพร้อมของ Tools และ Memberships ในบัญชีผู้เล่น (1000 = 1 วินาที)

วิธีใช้:
ลงส่วนขยายเบราว์เซอร์ Tampermonkey >> 
https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=th

แล้วกด Create a new script หลังจากนั้น Copy Paste
Ctrl+S หรือกด Save แล้วทดลองเข้าเว็บเล่นเกมได้ตามปกติ

สามารถตรวจสอบสคริปและแก้ไขได้เองตามใจชอบ
ผู้พัฒนาสคริปไม่ขอรับผิดชอบต่อความเสียหายใด ๆ
ที่อาจจะเกิดขึ้นกับบัญชีของท่านไม่ว่าเนื่องมาจากอะไรก็ตาม
หากท่านใดอยากที่จะบริจาคให้ผู้พัฒนา
ผมก็ขอยินดีรับไว้ครับ 😊😊😊

Wax Account: zzmjk.wam

BSC & ETH Wallet: 0x4031072Fd5a9986507B939EE7291a7FBA419a439

ปล.มันจะกดไววิบวับนิดนึงนะครับแนะนำให้ย่อ Browser ของเราลงไปอย่าไปสนใจมันครับ 55555
