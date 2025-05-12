# Security-Rules
basic security  rule

# 1. Dont trust client (อย่าเชื่อ ไคลเอ็น)
   
   Do everything on the server because the client can change anything. For example, if the client sends a number, that number might be fake. So the server could receive a fake number that the client wants to send.
   
   ให้ทำทุกอย่างที่ฝั่งเซิร์ฟเวอร์ เพราะฝั่งไคลเอนต์สามารถเปลี่ยนแปลงข้อมูลได้ทุกอย่าง เช่น ถ้าไคลเอนต์ส่งตัวเลขมา ตัวเลขนั้นอาจเป็นตัวปลอมก็ได้ ดังนั้นเซิร์ฟเวอร์อาจได้รับตัวเลขปลอมที่ไคลเอนต์ตั้งใจส่งมา

# 2. Avoid NAN, 0/0, -100

   Avoid these numbers because they can break your game or system. This is a duplication method: NaN, 0/0, math.sqrt(-1), tonumber(nil) — these result in infinity or NaN, and even -100 can be used to dupe your game or system.

   หลีกเลี่ยงตัวเลขเหล่านี้ เพราะมันอาจทำให้เกมหรือระบบของคุณพังได้ นี่คือวิธีการทำซ้ำ (Duplication): NaN, 0/0, math.sqrt(-1), tonumber(nil) — ค่าพวกนี้จะได้ผลลัพธ์เป็น infinity หรือ NaN และแม้แต่ -100 ก็อาจถูกใช้เพื่อโกงหรือทำซ้ำในเกมหรือระบบของคุณได้
