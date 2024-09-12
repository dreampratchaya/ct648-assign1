# earthquake_app

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run start
```

This project was created using `bun init` in bun v1.1.26. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.


66130423 ปรัชญา ป้องกัน,
66130502 ปฏิวัติ สบายยิ่ง,
66130409 พิชิต  ทองดำ


หลักการออกแบบและการทำงานใช้ข้อมูล รายงาน Earthquake โดยการแสดงข้อมูลจากการเลือกวันที่ข้อมูลจะถูกเปลี่ยนไปตามวันที่เลือก โดนไม่ได้มีการ Refresh Screen !!! โดยเลือกใช้งาน Server Express รูปแบบ CSR 

หลักการคือ Server จะส่งไฟล์ Index.html + Java script ไปให้กับ Client ทำการ Run Java script ที่ Local 

หลักการออกแบบ Quick Step 
  1. ดึงข้อมูลจาก API มาจาก "https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&starttime=2020-01-01&endtime=2020-01-02"
  2. จากนั้นทำการ Reture data จาก Loop ออกมาตามวันที่เรา Select date 






