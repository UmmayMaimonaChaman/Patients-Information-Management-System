# -Patients-Information-Management-System
Python (using Dummy Headed Doubly Circular Linked List)


DESCRIPTION:

In this project, I have implemented a waiting room management system in an emergency ward of a hospital. My program will serve a patient on a first-come-first-serve basis. 

Here I have added,
WRM (waiting room management) class that will contain the below methods:

RegisterPatient(id, name, age, bloodgroup): This method will register a patient into this system. The method will create a Patient type object with the information received as a parameter. That means this method will add a patient-type object to our linked list.

ServePatient(): This method calls a patient to provide hospital service for him/her. In this method, we need to ensure that we serve the patient first who was registered first.

CancelAll(): This method cancels all patients' appointments so that the doctor can go to lunch.

CanDoctorGoHome(): This method returns true if no one is waiting, otherwise, returns false.

ShowAllPatient(): This method prints all names of the waiting patients in sequential order. It means the patient who got registered first, will come first, and so on.

ReverseTheLine(): This method reverses the patient's line. It means the patient who got registered last, will come first, and so on.



There is a Tester code that will interact with users and get information about patients. This will pass this information to WRM and create instances of patients in WRM and call the methods of WRM class. 



Tester Code Options:

Add Patient – print Success or Not

Serve Patient – print Name of Patient being Served 

Show All patients – print all patients in sequence to serve

Can Doctor go Home? – return yes or no

Cancel all Appointment – print Success or Not

ReverseTheLine - print Success or Not
