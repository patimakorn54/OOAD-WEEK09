OOAD-WEEK09 นายปฏิมากร บุญเปลี่ยน 57030190

ส่งการบ้าน Class Diagram

ภาพที่ 1 Person
```
Code
```
```
@startuml
Person <|-- Address

Person : -Name
Person : -Id Number
Person : -Religion
Person : -Address
Person : +Color Hair()
Person : +Skin color()

Address : -Street
Address : -City
Address : -Postal Code

@enduml
```
![]
(https://github.com/patimakorn54/OOAD-WEEK09/blob/master/HomeWork/1.png?raw=true)

ภาพที่ 2 รถยนต์
```
Code
```
```
@startuml
Car  "1" --* "1"  Engine


Car : -Model Engine
Car : -Id Car
Car : Start()
Car : Stop()
Car : Seat()

Engine : -piston
Engine : -Cylinder head

@enduml
```
![]
(https://github.com/patimakorn54/OOAD-WEEK09/blob/master/HomeWork/2.png?raw=true)

ภาพที่ 3 TelePhone
```
Code
```
```
@startuml
Telephone  --  Baterry
Telephone  --  MicroPhone
Telephone  --  Screen

@enduml
```
![]
(https://github.com/patimakorn54/OOAD-WEEK09/blob/master/HomeWork/3.png?raw=true)

ภาพที่ 4 Home
```
Code
```
```
@startuml
Home  --  Windows
Home  --  Door
Home  --  Bed

Home :  -BedRoom
Home :  -BathRoom
Home :  -Kitchen
Home :  +Stay()
@enduml
```
![]
(https://github.com/patimakorn54/OOAD-WEEK09/blob/master/HomeWork/4.png?raw=true)

ภาพที่ 5 School
```
Code
```
```
@startuml
School  -->  field
School  -->  Class
School  -->  toilet

School  :  +Teacher
School  :  +Student
School  :  +Study()
@enduml
```
![]
(https://github.com/patimakorn54/OOAD-WEEK09/blob/master/HomeWork/5.png?raw=true)
