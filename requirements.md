# Software Requirements

## Vision

- What is the vision of this product?
  - To help those seeking emergency care receive timely care at a hospital based on the seriousness of their condition

- What pain point does this project solve?
  - It allows medical personnel at the hospital ER to orginze patient flows into queues and prioritize providing care 

- Why should we care about your product?
  - Everone requires medical attention at some point in their lives. Most of us have been to an ER having to wait in line for a long time to receive care. Those who need care faster should be put to the front of the line and be seen by a provider faster. Potentially, this app can also help divert some walk-in patients to less busy ER departments in their area by providing the info of how busy each of them is.
  
## Scope (In/Out)

- IN - What will your product do?
  - Authorization/authentication - Let medical personnel create and access role-based accounts
  - Assign patient priority level based on presenting signs and symptoms
  - Ability to change the priority in case symptoms get worse/better
  - Queue patients
  - Dequeue patients
  - Present overall number of patients in the queue to unauhtenticated/unauthorized users
- OUT - What will your product not do?
  - This app will not sell products
  - This app will not be used for in-patient care management

## Minimum Viable Product

- What will your MVP functionality be?
  - Have a front-end UI that lets the triage medical personnel input overal presenting signs and symptoms and assign priority level
  - Ability to change the priority level while the patient is in the queue
  - Use a database to store data
  - Have user auth 
  - Let providers on the other end see which patients are in line, their assigned priority level and ability to remove these patients from the queue
- What are your stretch goals?
  - Show users how busy the emergency rooms are in the area
- What stretch goals are you going to aim for?

## Functional Requirements

1. The app serves two authorized roles: a receptionist/triage and a provider. Both roles can authenticate and receive the appropriate authorization based on their role.
2. The app also allows unauthorized guests to see toatl number of patients waiting to be seen and approximate wait times
3. Front-desk medical personnel (receptionist) can create new patients and enter their data, such as name, age, and the reason for visit
4. A triage nurse can place a patient into the queue, and assign apriority level based on the reason for visit/severity of symptoms
5. A triage nurse can reassign the patient's priority level
6. The app allows for multiple receptionists and providers to use the app at the same time.
