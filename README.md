# Double Circular Linked List
## Introduction
This is a program developed in Assembly for MIPS R2000, which consists in making a double circular linked list as shown here:
<br>
![image](https://github.com/JamesBond-01/CircularLinkedList-Assembly/assets/72282343/61e84e2d-9bde-4ead-9464-23fc7d4d18d9)
<br>
## Features
### Menu
1) Create a new category
2) Select previous category
3) Select next category
4) Show existing categories
5) Delete current category
6) Add an object to the selected category
7) Show every object in the current category
8) Delete an object of the chosen category by using object's ID

### Error Codes
#### 1xx: Option error
- 101: Invalid selected option

#### 2xx: Selecting categories
- 201: There are no categories in existance
- 202: Only one category existing

#### 3xx: Showing categories
- 301: There are no categories to show

#### 4xx: Deleting categories
- 401: There are no categories to delete

#### 5xx: Adding objects to categories
- 501: There are no categories to add the object

#### 6xx: Showing objects from category
- 601: There are no categories to show its objects
- 602: There are no objects to show

#### 7xx: Removing objects from category
- 701: There are no categories to delete its object

#### notFound: Provided ID not found
