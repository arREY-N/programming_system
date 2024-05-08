askNCR 

Functions

1. Log-in/Sign up
    a. Student/Nurse Accounts
    b. Admin/Developer Accounts
2. Symptom Search
    a. Term Matching Algorithm
3. New Symptom File Creation
    a. Template
4. Patient Information Management
    a. Name
    b. History
    c. Allergies
    d. Charts
    e. Nursing Care Recommendations
5. Care Document Generation
    a. Symptoms
    b. Care Recommendations
    c. Pathogenesis (?)


FLOWCHART
1a. Log in 
    a. Enter correct nurse/student number
    b. Enter correct password

        Case A: No user found
        Case B: Incorrect password
        Case C: Successful log in 

        Exception: InvalidCharacterInputException()
        
1b. Sign up
    a. Enter valid nurse/student number
    b. Enter valid password

        Case A: Existing user
        Case B: Successful sign up

        Exception: InvalidCharacterException()

2a. Menu Screen (Student/Nurse)
    Option A: Patient List (per nurse)
    Option B: Symptom Search
    Option C: New Symptom

2b. Menu Screen (Admin/Developer)
    Option A: Nurse Accounts
    Option B: Symptom Database
    Option C: New Symptom


Symptom Template