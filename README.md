# Basic of DNA Analysis [Bioinformatics]

[![dna.png](https://i.postimg.cc/5t5jGSnM/dna.png)](https://postimg.cc/kV4nR80j)

## What is Bioinformatics?
Bioinformatics หรือชีวสารสนเทศ เป็นสาขาที่เกิดขึ้นจากการประยุกต์ใช้คอมพิวเตอร์ทางชีววิทยาการแพทย์ โดยเน้นปัญหาการเก็บ, รวบรวม, และวิเคราะห์ข้อมูลรหัสพันธุ์กรรม. การใช้เทคโนโลยีสารสนเทศร่วมกับวิทยาศาสตร์การคำนวณ (computational science) ช่วยให้การทำงานและวิจัยด้านนี้เป็นไปอย่างก้าวหน้าและมีประสิทธิภาพ ตัวอย่างงานชีวสารสนเทศ อย่างเช่น โครงการถอดรหัสพันธุกรรมมนุษย์ (Human Genome Project), การถอดรหัสพันธุกรรมเชื้อโรคหรือพืชที่สำคัญ, และการผลิตยาใหม่ เป็นต้น.

การเขียนโค้ดเพื่อทำ DNA Analysis นี้ผมได้ใช้ภาษา python และใช้ไลบารี่ Biopython เพื่อช่วยคำนวณ เพราะตัว Biopython จะมีคำสั่งต่างๆที่สามารถใช้ในการทำงานด้าน DNA Analysis ได้ 
สำหรับไฟล์ Sequence DNA ผมจะใช้ไฟล์ .fasta ครับ ซึ่งเป็นไฟล์ที่นิยมนำมาใช้กัน
โดย dataset ด้าน DNA นำมาจาก NCBI , genBank ในโค้ดนี้ผมเอา Sequence ของโรค COVID-19 มาทำการเขียนโปรแกรม

บทความนี้ ถ้าผิดพลาดประการใดผมต้องขออภัยด้วยนะครับ ขอบคุณครับ 
Reference : 
- https://biopython.org/wiki/Documentation
- https://www.ncbi.nlm.nih.gov/nuccore/1798174254
- https://www.si.mahidol.ac.th/simi/bioinfo/bi_what.html#:~:text=%E0%B8%8A%E0%B8%B5%E0%B8%A7%E0%B8%AA%E0%B8%B2%E0%B8%A3%E0%B8%AA%E0%B8%99%E0%B9%80%E0%B8%97%E0%B8%A8%20(bioinformatics)%20%E0%B9%80%E0%B8%9B%E0%B9%87%E0%B8%99%E0%B8%AA%E0%B8%B2%E0%B8%82%E0%B8%B2,%E0%B8%AD%E0%B8%A2%E0%B9%88%E0%B8%B2%E0%B8%87%E0%B8%81%E0%B9%89%E0%B8%B2%E0%B8%A7%E0%B8%AB%E0%B8%99%E0%B9%89%E0%B8%B2%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%A1%E0%B8%B5%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B8%AA%E0%B8%B4%E0%B8%97%E0%B8%98%E0%B8%B4%E0%B8%A0%E0%B8%B2%E0%B8%9E.
