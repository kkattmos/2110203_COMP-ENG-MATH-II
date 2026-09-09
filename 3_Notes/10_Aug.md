ทวนของเก่า
x[n], x(t), period
delta(t), delta[n]

สมบัติ Sampling, Sifting, Scaling
delta(t -> 0) => inf
delta[n -> 0] => 1
# Lecture 2 - Convolution

ผลลัพธ์ที่ได้จาก Convolution -> "ระบบ?"
- ระบบการเปิดปิดไฟ
- Volume up & down
- Image Feature detection

หุ้น -> Moving Average ดูค่า average แบบกว้าง ๆ 

มี 6 ระบบ แต่จะไป Focus ที่ 2 อันแรกใน Slide
### Lineraity
(เส้นตรง?)

x_1(t) -> y_1(t)
x_2(t) -> y_2(t)

if x_3(t) = x_1(t) + x_2(t) ->  y_3(t) = y_1(t) + y_2(t) , linear!

(และเงื่อบไขต้อง apply เมื่อมีการ scale multiplication กับ x_1(t) และ x_2(t)

Examples (ลองไป prove ดู)
- คูณด้วย scalar constant -> **Linear**
- ยกกำลัง 2 -> **Not Linear**

ตัวอย่างอื่น ๆ ของ discrete 
### Time-varying
//

### System with(out) memory
 Memoryless = output ขึ้นกับเวลาเดียวกันเท่านั้น
 A system with memory = output ขึ้นกับเวลาก่อนหน้าด้วย
 - Ex: accumulator
 - y ขึ้นกับเวลาในอนาคต

### Causal
ได้ตั้งแต่อดีต - ปัจจุบัน
ดังนั้น memory จะเป็น causal ด้วย

### Invertibility
x(t) -system-> y(t) -inverse->x(t)

### Stable (Bound in Bound Out)
- มีขอบเขต บอกได้ว่าไม่เกินค่าไหน (ต้องไม่เกิน infinity)
- output ก็ถูก bound ที่ค่านั้นด้วย
- Ex: unit step (bound ไม่เกิน 1 แน่นอน)

// Convolution
คลาสนี้ไม่ต้อง Prove แต่ให้เน้นไปใช้ได้เลย

Page 11
วาด h[k] -> h[-k] -> h[n-k]

Tabular Method
function?

ดู Exercise 2.1, 2.2

Continuous Time signal
Exercise 2.3




