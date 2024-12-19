# **Cryptography**

# **CISSP Glossary - Student Guide**
- https://www.isc2.org/certifications/cissp/cissp-student-glossary
   - Secret writing. Today provides the ability to achieve confidentiality, integrity, authenticity, non-repudiation, and access control.
 
   - **ChatGPT**
      - การเขียนแบบลับ
ในปัจจุบัน การเขียนแบบลับสามารถให้คุณสมบัติต่าง ๆ ได้แก่ การรักษาความลับ (Confidentiality) ความถูกต้องสมบูรณ์ของข้อมูล (Integrity) การยืนยันตัวตน (Authenticity) การป้องกันการปฏิเสธความรับผิดชอบ (Non-repudiation) และการควบคุมการเข้าถึง (Access Control)
   - **Gemini**
      - การเขียนลับ
ในปัจจุบัน การเขียนลับสามารถช่วยให้เราบรรลุเป้าหมายด้านความปลอดภัยข้อมูลได้หลายประการ อาทิ ความลับ ความสมบูรณ์ ความถูกต้อง การปฏิเสธไม่ได้ และการควบคุมการเข้าถึง


# **Gartner Glossary**
- https://www.gartner.com/en/glossary/all-terms
   - In this cryptography method (also known as symmetric-key cryptography), the single key needed to encrypt and decrypt messages is a shared secret between the communicating parties. The biggest problem with this method is that the secret key must be communicated through an external mechanism separate from the communication channel over which the encrypted text flows. In addition, secret-key systems do not support digital signatures. These limitations are addressed in public-key cryptography (see separate entry).

   - **ChatGPT**
      - วิธีการเข้ารหัสนี้ (หรือที่เรียกว่าการเข้ารหัสแบบกุญแจสมมาตร) ใช้กุญแจเพียงชุดเดียวในการเข้ารหัสและถอดรหัสข้อความ โดยกุญแจนี้จะต้องถูกเก็บเป็นความลับและแชร์ร่วมกันระหว่างผู้ที่ทำการสื่อสาร ปัญหาหลักของวิธีนี้คือการถ่ายทอดกุญแจลับจำเป็นต้องทำผ่านช่องทางภายนอกที่แยกจากช่องทางการส่งข้อความที่เข้ารหัส นอกจากนี้ ระบบที่ใช้กุญแจลับยังไม่รองรับการสร้างลายเซ็นดิจิทัล ซึ่งข้อจำกัดเหล่านี้ถูกแก้ไขในระบบการเข้ารหัสแบบกุญแจสาธารณะ (ดูรายละเอียดเพิ่มเติมในหัวข้อที่เกี่ยวข้อง)

   - **Gemini**
      - การเข้ารหัสแบบกุญแจเดียว
วิธีการเข้ารหัสนี้ (หรือที่เรียกว่า การเข้ารหัสแบบกุญแจสมมาตร) ใช้กุญแจเดียวในการทั้งเข้ารหัสและถอดรหัสข้อความ ซึ่งเป็นความลับร่วมกันระหว่างคู่สื่อสาร ปัญหาใหญ่ที่สุดของวิธีนี้คือ กุญแจลับต้องถูกส่งผ่านช่องทางภายนอกแยกต่างหากจากช่องทางการสื่อสารที่ข้อความเข้ารหัสไหลผ่าน นอกจากนี้ ระบบกุญแจลับยังไม่รองรับลายเซ็นดิจิทัล ข้อจำกัดเหล่านี้ได้รับการแก้ไขในระบบการเข้ารหัสแบบกุญแจสาธารณะ (ดูรายละเอียดเพิ่มเติม)


# **Myself**
   - สรุป Cryptography คือวิธีการแปลงข้อมูลให้เป็นรหัสที่เข้าใจยาก เพื่อป้องกันข้อมูลจากคนที่ไม่ได้รับอนุญาต และ การเข้ารหัสแบบคีย์สมมาตรเหมาะกับงานที่ต้องการความเร็วและการประมวลผลข้อมูลจำนวนมาก แต่ก็ควรใช้งานร่วมกับคีย์สาธารณะในกรณีที่ต้องการความปลอดภัยสูงหรือระบบที่มีคนใช้จำนวนมากครับ


# **Sample in Daily life**
   - การทำธุรกรรมออนไลน์
   - การใช้แอปพลิเคชันบนมือถือ
   - การส่งอีเมล
