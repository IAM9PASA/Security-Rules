# Security-Rules
basic security rule

1. dont trust client (อย่าเชื่อ ไคลเอ็น)
   Do everything on the server because the client can change anything. For example, if the client sends a number, that number might be fake. So the server could receive a fake number that the client wants to send.
   
   ให้ทำทุกอย่างที่ฝั่งเซิร์ฟเวอร์ เพราะฝั่งไคลเอนต์สามารถเปลี่ยนแปลงข้อมูลได้ทุกอย่าง เช่น ถ้าไคลเอนต์ส่งตัวเลขมา ตัวเลขนั้นอาจเป็นตัวปลอมก็ได้ ดังนั้นเซิร์ฟเวอร์อาจได้รับตัวเลขปลอมที่ไคลเอนต์ตั้งใจส่งมา
