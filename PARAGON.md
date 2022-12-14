![Gerard](self.jfif)
## **Gerard Lucas** - Senior Software Developer
---
[Home](README.md) | [EJ Gallo](GALLO.md) |
**Paragon Industries** |
[Meridian Medical](MERIDIAN.md) |
[Innovative ECMO](ECMO.md)  

---

![Paragon Logo](https://i.imgur.com/IJ1folB.jpg)

### **Paragon Industries Project** - Complete MES / ERP Solution 

#### **Project Details**

Created a company-wide MES and ERP system that manages the scheduling, production, auditing,  
sales, and shipping of tubular steel for a major producer of oil line pipe, ASTM, structural piling, and sprinkler pipe.  

Created API to return quality assurance data to Paragon customers:

``` js
let findPipe = function (barcode) {
  return Paragon.QA.pipeDetail(barcode, API_KEY);
};

const pipe = findPipe('P9999J0001');
console.log(pipe.status);
```

#### **Technologies Used**

+ ASP.NET
+ AngularJS
+ MS SQL Server
+ GE Cimplicity
+ OPC
+ SignalR
+ SSRS
+ SSIS

