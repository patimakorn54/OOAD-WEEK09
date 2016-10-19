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
()

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
()

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
()

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
()

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
()
