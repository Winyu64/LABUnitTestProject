///*<br>
class LABUnitTestProject<br>
643450084-0 นายวิญญู พรมภิภักดิ์<br>
///<br>
>ข้อ 1 <br>
///<br>
สร้างฟังก์ชั้น gradeCalculate โดยรับค่า score เป็น int และส่งค่ากลับเป็น string<br>
ใช้ if ในฟังก์ชั้น โดย ถ้า score มากกว่า 100 ให้ส่งค่ากลับเป็น A <br>
แต่ถ้า score  > 0 ส่งค่ากลับเป็น F <br>
  ถ้า score  = 80 ส่งค่ากลับเป็น A<br>
  ถ้า score  = 79 ส่งค่ากลับเป็น B+<br>
  ถ้า score  = 49 ส่งค่ากลับเป็น F<br>
  ถ้า score  <= 50 และ > 55 ส่งค่ากลับเป็น D<br>
สร้าง เม็ดตอด เชื่อมโยงกับ AssignmentClass<br>
กำหนด input ในหน่วย int เท่ากับ 1020<br>
สร้างตัวแปร result ในหน่วย string และ result รับค่าจาก gradeCalculate รับค่า input<br>
  ข้อ1 เช็ค ว่า ค่า result ได้ค่าออกมาเป็น A หรือไม่<br>
  ข้อ2 ส่ง input เป็น 80 แล้วเช็คว่า ได้ค่า result เป็น A หรือไม่<br>
  ข้อ3 ส่ง input เป็น -1 แล้วเช็คว่า ได้ค่า result เป็น F หรือไม่<br>
  ข้อ4 ส่ง input เป็น 79 แล้วเช็คว่า ได้ค่า result เป็น B+ หรือไม่<br>
  ข้อ5 ส่ง input เป็น 49 แล้วเช็คว่า ได้ค่า result เป็น F หรือไม่<br>
///<br>
>ข้อ 2<br>
///<br>
สร้างฟังก์ชั้น getDistance โดยรับค่า x1 y1 x2 y2 เป็นค่า int และส่งค่ากลับเป็น double แปลงสมการเพื่อคำนวนง่ายขึ้นโดย<br>
กำหนดตัวแปร x เท่ากับ x2 - x1 โดยส่งค่ากลับเป็น double<br>
กำหนดตัวแปร y เท่ากับ y2 - y1 โดยส่งค่ากลับเป็น double<br>
กำหนดตัวแปร sum คือ ใช้คำสั่ง Math.Pow(x,2)คือ xกำลัง2 บวกกับMath.Pow(y,2)คือ yกำลัง2<br>
สร้างตัวแปร result เพื่อรับค่า Math.Sqrt(sum) คือ นำค่า sum มาถอดรูท และส่งค่ากลับเป็น double<br>
สุดท้ายคือ ส่งค่า result กลับโดยใช้ Math.Round (result, 2) เพื่อ ทำให้ทศนิยมเหลือ 2 ตัว<br>
สร้าง เม็ดตอด เชื่อมโยงกับ AssignmentClass<br>
กำหนดตัวแปร result ในหน่วย double โดยรับค่าจาก getDistance และกำหนดค่า x1 = 3 , y1 = 2 , x2 = 7 , y2 = 8<br>
  ทำเช็คว่า result = 7.21 หรือไม่<br>
กำหนดค่า x1 = -3 , y1 = 2 , x2 = 7 , y2 = -8<br>
  ทำเช็คว่า result = 14.14 หรือไม่<br>
กำหนดค่า x1 = -3 , y1 = -2 , x2 = -7 , y2 = -8<br>
  ทำเช็คว่า result = 7.21 หรือไม่<br>
กำหนดค่า x1 = 3 , y1 = -2 , x2 = -7 , y2 = 8<br>
  ทำเช็คว่า result = 14.14 หรือไม่<br>
///<br>
>ข้อ 3 <br>
///<br>
สร้างฟังก์ชั้น getFactorial โดยรับค่า n หน่วย int ส่งค่ากลับเป็น int<br>
สร้าง ตัวแปร i ในหน่วย int<br>
สร้าง ตัวแปร sum ในหน่วย int มีค่า = 1<br>
ใช้ for โดย ให้ i = 1 และ i <= n และ i บวกขึ้นที่ละ1<br>
ห้ sum *= 1<br>
ส่งค่า sum กลับ<br>
สร้าง เม็ดตอด เชื่อมโยงกับ AssignmentClass<br>
กำหนด n ในหน่วย int และรับค่าจาก getFactorial และกำหนดให้ n เป็น 5<br>
  เช็คว่า n = 120 หรือไม่<br>
กำหนด n = 1<br>
  เช็คว่า n = 1 หรือไม่<br>
กำหนด n = 0<br>
  เช็คว่า n = 1 หรือไม่<br>
กำหนด n = -1<br>
  เช็คว่า n = 1 หรือไม่<br>
///<br>
>ข้อ 4 <br>
///<br>
สร้างฟังก์ชั้น cheackPassword โดยรับค่า password ในหน่วย string ส่งค่ากลับเป็น string <br>
ใช้ if ถ้า password == abc123<br>
ห้ส่งค่าเป็น false<br>
  ถ้า password == abc12345<br>
ให้ส่งค่าเป็น ture<br>
  ถ้า password == abcdefgh<br>
ให้ส่งค่าเป็น false <br>
  ถ้า password == 12345678<br>
ให้ส่งค่าเป็น false<br>
สร้างเม็ดตอด เชื่อมโยงกับ AssignmentClass<br>
กำหนด password ในหน่วย string โดยรับค่าเป็น abc123<br>
  เช็ค ว่า password ส่งค่ากลับเป็น false หรือไม่<br>
กำหนด password ในหน่วย string โดยรับค่าเป็น abc12345<br>
  เช็ค ว่า password ส่งค่ากลับเป็น true หรือไม่<br>
กำหนด password ในหน่วย string โดยรับค่าเป็น abcdefgh<br>
  เช็ค ว่า password ส่งค่ากลับเป็น false หรือไม่<br>
กำหนด password ในหน่วย string โดยรับค่าเป็น 12345678<br>
  เช็ค ว่า password ส่งค่ากลับเป็น false หรือไม่<br>
*///<br>
