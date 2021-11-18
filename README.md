# DWDM21

## Data Warehouse & Data Mining 2021

#### กัญญาวีร์ ศรีเทียมเงิน รหัสนักศึกษา 623020511-1

### Group Name : เอกาไร้สติ 

  กัญญาวีร์ ศรีเทียมเงิน รหัสนักศึกษา 623020511-1
  
  ชลธิชา ศาลางาม รหัสนักศึกษ 623020518-7
  
  สุภาภรณ์ บุตุธรรม รหัสนักศึกษา 623020543-
  
  จิราพร กลบรัตน์ รหัสนักศึกษ 623020762-6
  
  วิกานดา หงษ์บุญมี 623020764-2

# สารบัญ

* บทที่ 1 Introduction
  * [Lecture Introdution](https://github.com/Kanyawesr/DWDM21/blob/main/Chapter%201.pdf)
    * Data Warehouse 
    * Data Mining
    * Why Data Mining
    * ตัวอย่างข้อมูล
    * การเรียกชื่อ
    * ลักษณะภาพรวม
    * ขั้นตอนการทำข้อมูล
    * หัวข้อที่เรียน
* บทที่ 2 Getting to know your data
  * [Data Objects And Attribue Types](https://github.com/Kanyawesr/DWDM21/blob/main/2.1.pdf)
  * [Measuring Data Similarity And Dissimilarity](https://github.com/Kanyawesr/DWDM21/blob/main/Dissimilarity-distance-matrix.pdf)
  * [Binary Distance](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Distance-between-Data.pdf)
  * [Basic Python](https://github.com/Kanyawesr/DWDM21/blob/main/Data101Chapter2_1.ipynb)
    * Basic Python
      * Variables
    * Casting int() float() str()
    * Data Structure
      * การชี้ค่าใน list (indexing)
      * วิธีสร้าง list  แบบที่ 2 list ว่าง
      * list slicing
      * list + list
      * format string
    * Loop
      * Nested Loop
    * Condition (if statement)
      * Quiz 1
      * Homework 3
    * Function
      * Example
      * Quiz 
* [Pandas](https://github.com/Kanyawesr/DWDM21/blob/main/Data102Chapter2.ipynb)
    * Import pandas
    * คำสั่ง .head() .tail()
    * Box plot
      * Time series plot 
  * [Visualization](https://github.com/Kanyawesr/DWDM21/blob/main/Data_Visualization.ipynb)
    * Box plot
    * Scatter plot
    * Plot
    * Bar chart
      * Grouped barchart
      * Stacked barchart
    * Histogram  
  * [Distance_Numpy](https://github.com/Kanyawesr/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy Array
      * สร้าง Numpy array
      * สร้าง matrix เริ่มต้น
      * สร้าง matrix random
      * indexing & slicing
      * Useful functions
      * วนลูปเอง
      * Quiz กลุ่ม
    * Distance Matrix
      * Euclidean distance
      * Distance function
      * Manhattan distance
      * Quiz 6
      * HW11
      * Distance of binary value 
* บทที่ 3 Data preprocessing
  * [Lecture Data preprocessing](https://github.com/Kanyawesr/DWDM21/blob/main/Chapter%203%20Handling%20Missing.pdf) 
  * [Data Preprocessing](https://github.com/Kanyawesr/DWDM21/blob/main/Data_Preprocessing_(Chapter_3).ipynb)
    * Meta data
    * ชี้ข้อมูลในตาราง
      * แบบธรรมดา
      * แบบ .lioc[]
    * Missing Values
      * Handling Missing Value 1
      * Handling Missing Value 1.5
      * Handling Missing Value 2
      * Handling Missing Value 3
      * Handling Missing Value 4
      * Handling Missing Value 5
    * Pandas 
      * select data by values [PD]
        * สร้าง list ของ boolen
        * นำ list ของ boolen มาเลือกในตาราง
        * ใช้ & (and) และ (or) ในการรวม list ของ boolean
      * Quiz 4 + HW
      * Outlier
      * Quiz 5
      * Quiz กลุ่ม  
        * Pandas'looping(iterrows)
      * การรวมตาราง
        * รวม 2 ตาราง
        * เลือกเฉพาะ column ที่ต้องการมาแปะ
        * Group by (pandas)
      * HW + Quiz
        * [PD] save ตารางไปใช้ที่อื่น
        * [PD] การสร้างตาราง
* บทที่ 4 Data warehousing and on-line analytical processing
  * [Lecture Data warehousing and on-line analytical processing](https://github.com/Kanyawesr/DWDM21/blob/main/Data%20Cube%20%26%20OLAP.pdf)
    * Data Warehouse
    * Data Cubes
    * Typical OLAP Operations 
* บทที่ 5 Association rules
  * [Lecture Association rules](https://github.com/Kanyawesr/DWDM21/blob/main/Association%20rules.pdf)
  * [Reduced_marketbasket](https://github.com/Kanyawesr/DWDM21/blob/main/Chapter_6_Association_Rules.ipynb)
    * ความหมายของ Association Rule
      * Market Basket Analysis 
    * จัดการข้อมูลสินค้าที่ถูกยกเลิก
    * Basic Concepts
      * Fequence Pattern
      * Association Rule 
    * Efficient Pattern Mining Mathod
      * Apriori
      * Frequence Itemsets
    * Quiz 7   
* บทที่ 6 Classification
* บทที่ 7 Clustering
* MiniExam
* Group project
  * Project กลุ่ม
    * รายชื่อสมาชิกในกลุ่ม
    * แหล่งที่มาของข้อมูล
    * ปัญหา
    * ชุดข้อมูลที่ 1 รับเรื่องร้องเรียน/แจ้งเบาะแสยาเสพติด
      * คำอธิบายตาราง
      * ตรวจสอบค่า Missing ของตาราง data_01
    * ชุดข้อมูลที่ 2 ปริมาณของกลางยาเสพติด
      * คำอธิบายตาราง
      * ตรวจสอบค่า Missing ของตาราง data_02
    * ชุดข้อมูลที่ 3 จำนวนคดี ผู้ต้องหาคดียาเสพติด
      * คำอธิบายตาราง
      * ตรวจสอบค่า Missing ของตาราง data_03
    * ข้อมูลชุดที่ 4 ข้อมูลทั่วไปของจังหวัด
      * คำอธิบายตาราง
      * ตรวจสอบค่า Missing ของตาราง data_04
    * เชื่อมต่อตาราง
      * ตรวจสอบค่า Missing ของตาราง 2 ตารางที่เชื่อมต่อกันแล้ว
      * ตรวจสอบค่า Missing ของตาราง 3 ตารางที่เชื่อมต่อกันแล้ว
    * Classification
      * ปัญหา
      * เลือกคอลัมน์ที่ต้องการนำมาใช้งาน
      * Decision Tree
      * KNN
      * Neural Network
    * Evaluation
      * Retain & Evaluation
    * Data_Visualization
    * THE END
* [ไฟล์นำเสนอ Group Project](https://github.com/Kanyawesr/DWDM21/blob/main/Group-Project.pdf)
