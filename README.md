# Final_Project_643450067_0
ประวัติความเป็นมาของโปรแกรม
```

```
วัตถุประสงค์ของโปรแกรม
```
ใช้ในการกดบัตรคอนเสิร์ตและบันทึกข้อมูลของคนที่กดบัตร
```
### Class Diagram
```mermaid
classDiagram
direction RL
  class form1{
  buy()
  }
  class form2{
  -artist1
  -artist2
  -artist3
  goS1()
  goS2()
  goS3()
  }
  class S1{
  -number
  -name
  -amount
  -date
  buy()
  back()
  open()
  save()
  }
  class S2{
  -number
  -name
  -amount
  -date
  buy()
  back()
  open()
  save()
  }
   class S3{
  -number
  -name
  -amount
  -date
  buy()
  back()
  open()
  save()
  }
  class classS1{
  -
  open()
  save()
  }
  class classS2{
  -
  open()
  save()
  }
  class classS3{
  -
  open()
  save()
  }
  S1 --|> form2
  S2 --|> form2
  S3 --|> form2
  
  classS1 --|> S1
  classS2 --|> S2
  classS3 --|> S3
  
  form2 --|> form1
  ```
  เจ้าของโปรแกรม
  ```
  นาย เจษฎา ลีรัตน์ 643450067-0
