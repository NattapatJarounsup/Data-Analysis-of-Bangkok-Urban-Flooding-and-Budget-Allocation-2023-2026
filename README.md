# DataSci-ClimateChange
## Environmental problem

## Dataset source
- [Bangkok Budget by Project](bkk_budget_by_project.csv)
- [Bangkok Flood 50 Districts](bkk_flood_50_districts.csv)

## Data Cleaning and Transformation

## EDA

## Data Visualization
- [Data Visualization Python](Data%20Visualization/Data_Visualization_for_Project.ipynb)

(Top 10 Districts by Flood Count): กราฟแท่งแนวนอนแสดง 10 เขตแรกที่มีสถิติน้ำท่วมบ่อยที่สุด
<img src="Data%20Visualization/image/p1.png" width="500">

(Top 10 Districts by Total Budget): กราฟแสดง 10 เขตที่ได้รับงบประมาณรวมสูงสุด
<img src="Data%20Visualization/image/p2.png" width="500">

(Relationship Between Total Rainfall and Flood Count): กราฟจุด (Scatter Plot) แสดงความสัมพันธ์ระหว่าง "ปริมาณน้ำฝนรวม" กับ "จำนวนครั้งที่น้ำท่วม"
<img src="Data%20Visualization/image/p3.png" width="500">

(Drainage Dept vs District Office Budget): กราฟแท่งซ้อนทับ (Stacked Bar Chart) เจาะลึกงบประมาณของ 10 เขตแรก
<img src="Data%20Visualization/image/p4.png" width="500">

(Budget Allocation by Project Group): กราฟโดนัทแสดงสัดส่วนการเทงบประมาณไปกับโครงการประเภทต่างๆ
<img src="Data%20Visualization/image/p5.png" width="500">

(Distribution of Total Budget by Zone): กราฟ Box plot แสดงการกระจายตัวของงบประมาณเมื่อแบ่งตามโซนพื้นที่ (เช่น กรุงเทพฯ เหนือ, ใต้, ตะวันออก)
<img src="Data%20Visualization/image/p6.png" width="500">

(Total Accumulated Flood Count by Zone): กราฟแท่งแสดงจำนวนครั้งที่น้ำท่วมสะสมแบ่งตามโซน
<img src="Data%20Visualization/image/p7.png" width="500">

(Relationship Between Total Budget and Flood Count): กราฟจุดแสดงความสัมพันธ์ระหว่าง "งบประมาณที่ได้" กับ "จำนวนครั้งที่น้ำท่วม"
<img src="Data%20Visualization/image/p9.png" width="500">

## Environmental interpretation
1. ปัจจัยทางธรรมชาติและการรับมือของเมือง (Climate & Infrastructure Focus)

- ปริมาณน้ำฝนยังคงเป็นปัจจัยหลักที่กระตุ้นให้เกิดน้ำท่วมอย่างมีนัยสำคัญ (กราฟความสัมพันธ์ฝน-น้ำท่วม)
เมื่อดูจากงบประมาณ กรุงเทพฯ เลือกวิธีรับมือกับปัญหานี้ด้วย "โครงสร้างพื้นฐานสีเทา" (Grey Infrastructure) เป็นหลัก เช่น การสร้างเขื่อน กำแพงกั้นน้ำ ท่อระบายน้ำ และอุโมงค์ ซึ่งกินสัดส่วนงบประมาณไปกว่า 70%

- ข้อสังเกต: การทุ่มงบไปกับสิ่งก่อสร้างขนาดใหญ่อาจแก้ปัญหาได้ในบางจุด แต่อาจขาดความยืดหยุ่นในการรับมือกับสภาพอากาศที่เปลี่ยนแปลง (Climate Change) เมืองอาจต้องเริ่มพิจารณาการใช้พื้นที่สีเขียวหรือ "โครงสร้างพื้นฐานสีเขียว" (Green Infrastructure) เข้ามาช่วยซับน้ำเพิ่มเติม


2. ความเหลื่อมล้ำและประสิทธิภาพในการจัดสรรทรัพยากร (Resource Allocation & Equity)

- ข้อมูลชี้ให้เห็นถึง "ความไม่สอดคล้อง" (Mismatch) ระหว่างพื้นที่ที่รับความเสี่ยงสูงสุดกับพื้นที่ที่ได้รับเงินสนับสนุนมากที่สุด
ตัวอย่างที่ชัดเจนคือ เขตบางกะปิ ที่ประชาชนต้องเผชิญปัญหาน้ำท่วมบ่อยที่สุด แต่กลับได้รับงบประมาณอยู่ในระดับต่ำ ในทางกลับกัน เขตสวนหลวง กลับได้รับการอัดฉีดงบประมาณมหาศาล (ส่วนใหญ่จากสำนักการระบายน้ำ) ทั้งที่สถิติน้ำท่วมไม่ได้สูงที่สุด

- ข้อสังเกต: ความขัดแย้งของข้อมูลนี้นำไปสู่คำถามด้านนโยบายสิ่งแวดล้อมว่า การจัดสรรงบประมาณในปัจจุบันอิงตามความเดือดร้อนจริงของประชาชนในพื้นที่ (Data-driven decision) หรืออิงตามแผนการสร้างเมกะโปรเจกต์เฉพาะจุด ซึ่งอาจทำให้บางพื้นที่ถูกละเลย (Environmental Injustice)

3. บทสรุปเชิงนโยบาย (Policy Implication)

- การวิเคราะห์นี้ชี้ให้เห็นว่า ปัญหาน้ำท่วมในพื้นที่ไม่ได้เกิดจากข้อจำกัดทางสภาพอากาศเพียงอย่างเดียว แต่ยังเชื่อมโยงกับมิติของการบริหารจัดการเมือง ข้อมูลเสนอแนะว่าหน่วยงานที่เกี่ยวข้องควรมีการทบทวนเกณฑ์การกระจายงบประมาณให้เป็นธรรมมากขึ้น โดยมุ่งเป้าไปที่การบรรเทาทุกข์ในโซนที่วิกฤตที่สุดอย่างกรุงเทพฯ เหนือและกลาง พร้อมทั้งบูรณาการข้อมูลสถิติภัยพิบัติเข้ากับกระบวนการอนุมัติงบประมาณอย่างแท้จริง
