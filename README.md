# Customer Analytics for Credit Risk Profiling & Behavioral Segmentation

## 📌 Project Overview
This project applies **K-Means Clustering** to segment credit card customers based on their financial behaviors, such as spending habits, cash advance usage, and repayment capacity. The goal is to provide **Actionable Business Recommendations** for risk mitigation, debt management, and revenue growth.

**Tools & Technologies:**
* Python (Pandas, NumPy)
* Scikit-learn (K-Means Clustering, StandardScaler)
* Data Visualization (Matplotlib, Seaborn)

---

## Executive Summary & Actionable Recommendations

### 1. กลุ่มความเสี่ยงสูง (High-Risk Revolvers: Cluster 2)

* เป็นกลุ่มที่มีการใช้วงเงินเกือบเต็มวงเงิน มีการกดเงินสดสูง และมีสัดส่วนการชำระคืนต่ำกว่ากลุ่มอื่น แสดงถึงการขาดสภาพคล่องทางการเงิน

* Recommendation: ธนาคารควรใช้ระบบแจ้งเตือน 
และระงับการเพิ่มวงเงิน 
พร้อมทั้งรีบนำเสนอมาตรการปรับโครงสร้างหนี้ หรือเปลี่ยนยอดหนี้บัตรเครดิตเป็นสินเชื่อเงินผ่อนรายเดือน

* เพื่อป้องกันการเกิดหนี้เสีย (NPL)

## 2. กลุ่มพึ่งพาสินเชื่อ ยอดหนี้สูง (Credit-Dependent: Cluster 0)

* มียอดหนี้คงค้างและวงเงินสูง มีการพึ่งพาเงินสดล่วงหน้าบ้าง แต่ยังจ่ายชำระขั้นต่ำได้ ถือเป็นกลุ่มที่สร้างรายได้จากดอกเบี้ยให้กับธนาคาร

* Recommendation: ควรเฝ้าระวังพฤติกรรมการกดเงินสดอย่างใกล้ชิด (Monitoring) ถ้ามีการจ่ายล่าช้า ควรเสนอแคมเปญรวมหนี้ (Debt Consolidation) 

* เพื่อช่วยบรรเทาภาระดอกเบี้ยให้ลูกค้ายังสามารถผ่อนชำระต่อไปได้

## 3. กลุ่มทั่วไป ประวัติการเงินดี (Responsible Customers: Cluster 1)

* เป็นฐานลูกค้ากลุ่มใหญ่ที่สุด ใช้วงเงินน้อย ไม่ค่อยกดเงินสด และมีวินัยในการจ่ายเต็มหรือมากกว่าขั้นต่ำ

* Recommendation: นำเสนอแคมเปญส่งเสริมการขายแบบเจาะจง (Targeted Promotions) 
อย่างการให้ Cash Back หรือคะแนนพิเศษเมื่อมียอดใช้จ่ายถึงเกณฑ์ที่กำหนด 

* เพื่อกระตุ้นยอดการใช้จ่าย (Active Usage) และรักษาฐานลูกค้าไว้ได้

## 4. กลุ่มลูกค้าพรีเมียม กำลังซื้อสูง (Premium Active: Cluster 3)

* มียอดรูดซื้อสินค้าสูงที่สุดและมียอดหนี้คงค้างต่ำมาก เพราะลูกค้ามักจะชำระเต็มจำนวน เป็นกลุ่มที่สร้างรายได้จากค่าธรรมเนียมการรูดบัตรได้อย่างมาก

* Recommendation: ควรเน้นการรักษาความสัมพันธ์ระยะยาว (Retention) โดยการเสนอสิทธิพิเศษระดับ VIP อัปเกรดหน้าบัตร 
และนำเสนอผลิตภัณฑ์ทางการเงินอื่นๆ (Cross-selling) เช่น กองทุนรวม สินเชื่อบ้าน

* เพื่อโอกาสในการสร้างรายได้เพิ่มเติม และสามารถปรับปรุงความพึงพอใจของลูกค้า

## 📈 Strategic Summary

| Segment | Priority | Business Goal |
| :--- | :---: | :--- |
| **High-Risk Revolvers** | High | Risk Mitigation |
| **Credit-Dependent Customers** | Medium-High | Debt Management |
| **Responsible Customers** | Medium | Retention & Usage |
| **Premium Active Customers** | High | Revenue Growth & Cross-sell |
