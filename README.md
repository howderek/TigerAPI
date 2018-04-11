# TigerAPI
RestAPI for TigerHacks 2018 

## Group Members

* Melissa Hollingshed (Product Owner)
* Roger Kiew
* Morgan Knoch
* Christopher Wong (Scrum Master)
* Qiwen Guo
* Riley Evans


|Table|Type|
|---|---|
|id|integer|
|Prize Description|varchar(255)|
|Description To Win| varchar(255)|
|Number Of Prizes|int|
|Type Of Prize|enum('money','item')|
|Sponsor|int|

Table for sponsors:

|Table|Type|
|---|---|
|id|integer|
|Sponsor Name|varchar(255)|

