# practiceSNOW

Create an Application as "SRU" in Servicenow IDE

1. create a table "studentinformation" along with SRU Application
================================================================
fields:
name of the student - string - 40
rollno - string -40
contact - phone number  (no size)
department - choice - (I will tell u how to add choice list using form design) make option as with None
address - string - 40
emailid - string - 40
Date Of Birth - date 

create an application with the above mentioned fields.
======================================================

using studio add one more field to studentinformation table i.e.,  Add Phote - datatype is (image). [ we can not add image type with the application creation]

Intigrate this application with github with "SRU_Information"
============================================================


2. create a new table "Visitors " under "SRU" Application menu: (studio -> create application file- > select table item )
=====================================================================================================================

visitor table maintains the information of SRU College visitors : 

fields:
name: string type with 40 charecters of length
email: email address of visitos
phone number: contact number of visitors
indate: date datatype 
intime: time datatype
outdate: date datatype
outtime : time datatype 
purpose of visit: string
whom to meet: string
