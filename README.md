# service-oriented-Architecture
Mash up จากการใช้ OpenWeather กับ Yandex translate API เพื่อค้นหาสภาพอากาศของเมือง หรือ จังหวัดต่างๆ จากนั้น สามารถแปลงผลลัพธ์ จากภาษาอังกฤษ ไปได้อีก 5 ภาษา
โดยเป็นการใช้ Open weather map API แบบ subscribe เป็น Free โดยสามารถเรียก request ได้ 60 ครั้ง ต่อ 1 นาที สามารถรับ API key ได้ด้วยการลงทะเบียนเป็น Member แบบ Free สำหรับ Developer มีข้อมูลของเมืองและสถานที่กว่า 200,000 แห่ง จากสถานีอุตุนิยมวิทยา 40,000 แห่งทั่วโลก
การใช้งานตัวอย่าง คือ http://api.openweathermap.org/data/2.5/weather?q=phuket&appid=2d06ab6c40757b1d2349d6d35807c47f&&units=metric เป็นการเรียกโดยใช้ Method GET ใน HTTP ผ่าน URL ข้างต้นโดยหลัง ข้อความ weather?q= ให้ใส่ ข้อความตัวแปร สถานที่ที่ต้องการหา แล้วตามด้วย API KEY ที่รับหลังจาก ลงทะเบียนเรียบร้อยแล้ว
