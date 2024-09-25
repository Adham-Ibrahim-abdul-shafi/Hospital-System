# Hospital Management System

This is a simple Hospital Management System implemented in C++. The program allows managing patient queues based on different specializations. Each specialization can handle a limited number of patients, and patients can either be regular or urgent. The system is designed to simulate the process of adding new patients, printing patient queues, and getting the next patient for treatment.

## Features

- **Add New Patient:** Patients can be added to the queue, either as regular or urgent cases. Regular patients are added to the end of the queue, while urgent patients are given priority and added to the beginning.
- **Print All Patients:** Lists all patients in each specialization, showing their names and urgency status (regular or urgent).
- **Get Next Patient:** Retrieves the next patient in line (based on priority) and removes them from the queue for treatment.
- **Queue Management:** Handles queue shifts when adding urgent patients or serving patients to ensure proper queue management.

## System Limitations

- There are a maximum of 20 specializations (indexed 1-20).
- Each specialization can only handle a maximum of 5 patients in its queue.
- Patients can either be regular (added to the end of the queue) or urgent (added to the front).

