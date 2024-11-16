# EXNO8AI
Logic Programming –  Medical Diagnosis Expert System
### DATE: 16-09-2024

### REGISTER NUMBER : 212221060180
### AIM: 
Write a Prolog program to build a medical Diagnosis Expert System.
###  Algorithm:
1. Start the program.
2. Write the rules for each diseases.
3. If patient have mumps then symptoms are fever and swollen glands.
4. If patient have cough, sneeze and running nose then disease is measles.
5. if patient have symptoms headache ,sneezing ,sore_throat, runny_nose and  chills then disease is common cold.
6. Define rules for all disease.
7. Call the predicates and Collect the symptoms of Patient and give the hypothesis of disease.
        

### Program:
```
hypothesis(Patient,german_measles) :-
symptom(Patient,fever),
symptom(Patient,headache),
symptom(Patient,runny_nose),
symptom(Patient,rash).
hypothesis(Patient,flu) :-
symptom(Patient,fever),
symptom(Patient,headache),
symptom(Patient,body_ache),
symptom(Patient,conjunctivitis),
symptom(Patient,chills),
symptom(Patient,sore_throat),
symptom(Patient,runny_nose),
symptom(Patient,cough).
hypothesis(Patient,common_cold) :-
symptom(Patient,headache),
symptom(Patient,sneezing),
symptom(Patient,sore_throat).
hypothesis(Patient,chicken_pox) :-
symptom(Patient,fever),
symptom(Patient,chills),
symptom(Patient,body_ache),
symptom(Patient,rash).
hypothesis(Patient,measles) :-
symptom(Patient,cough),
symptom(Patient,sneezing),
symptom(Patient,runny_nose).
symptom(raju,headache).
symptom(raju,sneezing).
symptom(raju,sore_throat).
```

### Output:

![image](https://github.com/user-attachments/assets/0b36fba8-24dd-4d81-b10b-9f4476521f48)


### Result:
Thus the simple medical diagnosis system was built sucessfully.
