# exp-crud
======================express node crud project======================================
Download zip file & extract zip file & follow below steps
1]Requirments:-

MongoDB database named exp-crud

Node version above and Eqaul 11

[2] Download code, install packages, and then hit command as npm start.

[3] Description and test cases of each API:

A]getbookdetails(GET) :-

It fetches specific and all records.

Ex:- 
I] Directly hit the search button of Postman, and then you will get all records.
II]Pass an ID in it, then search, and you will get a specific record.
getbookdetails?id=1

B]savebookdetails(POST) :-

It does not save duplicate records.
IN BODY PASS BELOW PARAMETERS:

{
"title": "==The Girl on the Train",
"author": "Paula Hawkins",
"Summary": "A psychological thriller that revolves around three women whose lives become intertwined through a series of secrets, lies, and the mystery surrounding a woman's disappearance."
}

C]updatebookdetails(PUT) :-

It sends an error response in case any record is not found.

IN BODY PASS BELOW PARAMETERS:

{
"title": "The Girl on the Train",
"author": "Paula Hawkins",
"Summary": "A psychological thriller that revolves around three women whose lives become intertwined through a series of secrets, lies, and the mystery surrounding a woman's disappearance.",
    "id": 9
}

D]deletebookdetails(DELETE) :-
I] Pass an ID in it as shown below:
deletebookdetails?id=11
II] If the record dose is not found, it will simply show an error response.


Note (Test Cases):

ID will be required in the update and delete API.
Only numbers are allowed.


That's all, I mentioned only the important points. Thank You!
