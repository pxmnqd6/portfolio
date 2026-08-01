คุณคือ Senior Front-end Web Developer expert ที่มีความเชี่ยวชาญด้าน UI/UX และ Responsive Design โปรดสร้างโค้ดสำหรับเว็บไซต์ Portfolio แบบหน้าเดียว (One-Page) สำหรับยื่นสมัครเข้าศึกษาต่อ "คณะแพทยศาสตร์ จุฬาลงกรณ์มหาวิทยาลัย" โดยปฏิบัติตามโครงสร้างและข้อกำหนดดังต่อไปนี้อย่างเคร่งครัด:

### 1. Context (บริบทของโครงการ)
* โครงการ: เว็บไซต์พอร์ตโฟลิโอส่วนตัวยื่นสมัครเข้าศึกษาต่อ คณะแพทยศาสตร์ จุฬาลงกรณ์มหาวิทยาลัย (MDCU)
* กลุ่มเป้าหมาย: คณะกรรมการคัดเลือกและอาจารย์ผู้สัมภาษณ์ คณะแพทยศาสตร์ จุฬาฯ
* จุดประสงค์: นำเสนอประวัติ ความเจตจำนง (Passion) ผลงานทางวิชาการ กิจกรรมจิตอาสา และความเป็นผู้นำ ในรูปแบบเว็บไซต์ที่สะอาดตา ทันสมัย สะท้อนความน่าเชื่อถือ มุ่งมั่น และมีจริยธรรมทางการแพทย์

### 2. Clarity (สิ่งที่ต้องการชัดเจน)
สร้างไฟล์ HTML5 สมบูรณ์แบบ Single-Page Portfolio ภายในไฟล์ `index.html` เพียงไฟล์เดียว โดยใช้ Tailwind CSS ผ่าน CDN สำหรับสไตล์ และ Vanilla JavaScript สำหรับโต้ตอบพื้นฐาน (ไม่ใช้ Framework อย่าง React/Vue)

### 3. Specificity (รายละเอียดเฉพาะเจาะจง)
#### 3.1 Design & Theme Guidelines (MDCU Identity)
- Color Palette: 
  * Primary: สีชมพูจุฬาฯ (Chula Pink / Magenta เช่น `#E01E5A` หรือ `#D946EF` ผสมโทนชมพูเข้ม) สื่อถึงสถาบัน
  * Secondary: สีเขียวเข้มการแพทย์ / สุขภาพ (Medical Green เช่น `#0F766E` หรือ `#047857`) สื่อถึงการรักษาและความเอื้ออาทร
  * Neutral: สีขาวและเทาสะอาดตา (Slate/Zinc) ให้ความรู้สึกสะอาด สว่าง และเป็นมืออาชีพ
- Typography: ใช้ฟอนต์ภาษาไทยสไตล์ Modern Minimal อ่านง่ายและเป็นทางการ เช่น 'Prompt' หรือ 'Sarabun' ผ่าน Google Fonts
- Responsiveness: ออกแบบด้วยแนวคิด Mobile-first รองรับการแสดงผลทุกขนาดหน้าจอ (Mobile, Tablet, Desktop) 100%

#### 3.2 โครงสร้างและส่วนประกอบ (Sections)
1. Header & Navigation:
   - Sticky Navbar ติดด้านบนเสมอเมื่อ Scroll
   - ฝั่งซ้าย: โลโก้หรือชื่อย่อสไตล์การแพทย์/จุฬาฯ
   - ฝั่งขวา: เมนูลิงก์ไปยังส่วนต่างๆ พร้อมฟังก์ชัน Smooth Scrolling
   - หน้าจอมือถือ: แสดง Hamburger Menu ที่กดเปิด-ปิดแถบเมนูได้ด้วย Vanilla JS
2. Hero Section:
   - แสดงผลเต็มหน้าจอ (Full-height) โทนสะอาดตา
   - พาดหัว (Headline): ชื่อ-นามสกุล ของนักเรียน (ว่าที่นิสิตแพทย์)
   - สโลแกน (Sub-headline): "Dedicated to Healing, Driven by Science | มุ่งมั่นสู่การเป็นแพทย์จุฬาฯ เพื่อสังคม"
   - ปุ่ม Call-to-Action สีชมพูจุฬาฯ/เขียวการแพทย์ เขียนว่า "สำรวจผลงานและแรงบันดาลใจ" เลื่อนไปยังส่วน About / Projects
3. About Me Section (แรงบันดาลใจ & ตัวตน):
   - Layout แบบ 2 คอลัมน์บน Desktop (ฝั่งหนึ่งเป็นรูปโปรไฟล์ชุดนักเรียน/ชุดกาวน์ฝึกงาน อีกฝั่งเป็นข้อความ)
   - ข้อความแนะนำตัว เน้น **Passion ทางการแพทย์**, จริยธรรม, เหตุผลที่อยากเรียนแพทย์ จุฬาฯ และเป้าหมายในการพัฒนาสุขภาวะของเพื่อนมนุษย์
4. Skills & Competencies Section:
   - นำเสนอในรูปแบบ Cards หรือ Icon Grid แบ่งหมวดหมู่ชัดเจน:
     * Academic Excellence: ชีววิทยา (Biology), เคมี (Chemistry), ภาษาอังกฤษ (English for Medicine)
     * Research & Practical Skills: การทำวิจัยพื้นฐาน, การทดลองห้องแล็บ, ทักษะปฐมพยาบาลเบื้องต้น (CPR/First Aid)
     * Soft Skills & Ethics: Empathy (ความเข้าใจมนุษย์), Critical Thinking, Communication, Teamwork & Leadership
5. Projects, Research & Activities Section:
   - Layout แบบ Card Grid (1 คอลัมน์บน Mobile, 3 คอลัมน์บน Desktop)
   - แสดงผลงาน/กิจกรรมรวม 10 ตัวอย่าง เช่น:
     1. โครงงานวิจัย/นวัตกรรมสุขภาพ (เช่น สารสกัดจากพืชชะลอแบคทีเรีย)
     2. การแข่งขันโอลิมปิกวิชาการ (สอวน. ชีววิทยา/เคมี)
     3. กิจกรรมจิตอาสาในโรงพยาบาล / ฝึกงานดูงานหน่วยแพทย์เคลื่อนที่
     4. ค่ายอยากเป็นหมอ (MDCU Open House / Medical Camp)
     5. กิจกรรมช่วยเหลือสังคม/ผู้สูงอายุ/ชุมชน
     6. งานสืบค้นและนำเสนอความรู้ทางการแพทย์ (Medical Review Article)
     ... (ใส่ผลงานตัวอย่างจนครบ 10 Cards)
   - แต่ละ Card ประกอบด้วย: รูปภาพ Thumbnail, ชื่อกิจกรรม, บทบาท/สิ่งที่เรียนรู้, Tag หมวดหมู่ (วิชาการ / จิตอาสา / วิจัย)
6. Contact & Footer Section:
   - โทนสีเรียบหรู นุ่มนวล
   - ข้อมูลการติดต่อ: อีเมล, เบอร์โทรศัพท์, โซเชียลมีเดีย/ช่องทางเผยแพร่ผลงานวิชาการ
   - ข้อความ Footer: "Copyright © 2026 [ชื่อนักเรียน]. All Rights Reserved. | MDCU Applicant"

### 4. Constraints (ข้อจำกัดและขอบเขตทางเทคนิค)
- Single File Constraint: ทั้งหมด (HTML, Tailwind CDN, Custom Style, Vanilla JS Script) ต้องบรรจุอยู่ในไฟล์ `index.html` เพียงไฟล์เดียว
- Clean Code & Documentation: ต้องเขียน Comment ภาษาไทย แบ่งแยกแต่ละ Section ชัดเจน เพื่อให้แก้ไขข้อมูลส่วนตัวได้ง่าย
- Asset Management: รูปภาพทั้งหมดใช้ Placeholder URL เช่น `https://placehold.co/600x400` หรือ Unsplash (ค้นภาพแนว Medical/Doctor/Lab)
- Compatibility: รองรับการรันผ่าน Extension "Live Server" บน GitHub Codespaces ได้ทันที