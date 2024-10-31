# CS489 – Applied Software Development
### Lab 2
**(April 2024)**

---

### 1.1 Functional Requirements Discovery

For the problem statement given above, perform Requirements discovery and identify the functional requirements for the system, and present them in a list of short statements.

#### Functional Requirements:

- **User Management**: The system should allow an Office Manager to register new Dentists and Patients.

- **Dentist Registration**: The system should allow the Office Manager to:
  - Assign a unique ID to each Dentist.
  - Record the Dentist’s First Name, Last Name, Contact Phone Number, Email, and Specialization.

- **Patient Enrollment**: The system should enable the Office Manager to:
  - Record a Patient’s First Name, Last Name, Contact Phone Number, Email, Mailing Address, and Date of Birth.

- **Appointment Request and Booking**:
  - Patients can request an appointment either by calling in or by submitting an online form.
  - The Office Manager can book the appointment based on the availability of the Dentist.
  - The system should send a confirmation email to the Patient after booking an appointment.

- **Appointment Management for Dentists**:
  - Dentists should be able to log into the system and view all their scheduled appointments, with details about the Patients.
  - The system should restrict appointments to a maximum of 5 per week per Dentist.

- **Surgery Information**:
  - The system should provide information about each Surgery location, including Name, Location Address, and Telephone Number.

- **Patient Portal**:
  - Patients should be able to log into the system to view their appointment details, including information about the Dentist.
  - Patients should be able to request to cancel or reschedule their appointments.

- **Billing Restriction**:
  - The system should prevent Patients from requesting new appointments if they have unpaid bills.

---

### 1.2 System Analysis & Design

Perform System Analysis & Design, and create a Domain model UML Class diagram for the software solution. In your model, make sure to include the appropriate attributes for each class, and the relationships and multiplicities and roles (where appropriate). 
