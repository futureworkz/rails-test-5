# Rails-test-5

## Create a database to store the information below:

#### School
```
Name
Address
Type (University, High school, Secondary School, Primary School)
```

#### Student:
```
Name *
DOB * (>=18)
Has many schools
```

#### Office Worker (white-collar worker)
```
Name *
DOB * (>=20)
Years of Experience * (>=0)
```
#### Assume:
John and Alex are students in the same school, Robert is a worker. The system must be provide these functions:
```
john.name
john.age
robert.years_of_exp
john.schoolmates  should include alex
```
Note: (*) is compulsory.
