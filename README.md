# Final-project-stuff

Strategy/approach to the project

Our Final Project was based on the development of the Cowboy Property Management system. This system enables admin, employees, and renters to manage information of the properties by accessing resident information and arranging the available apartment for rent. Admin/employees can keep track of information such as property units being rented vs available, current and prospective renters, leases and payments/overdue fees, maintenance requests, and employee info. Renters can also access information such as their leases and account information, personal information, and make payments. The system uses CRUD operations to accomplish these tasks.
The database contains the following tables:
“Employee” table (contains columns EMP_ID, Last, First, Position)
“Property“ table (contains columns PROPERTY_ID, Address, Manager)
“Unit“ table (contains columns UNIT_ID, UNIT_NUMBER, Bed, Bath, Price)
“Maintenance“ table (contains columns ID, UNIT_ID, EMP_ID, Date, Issue, Status)
“Lease“ table (contains columns LEASE_ID, RENTER_ID, EMP_ID, UNIT_ID, Price, Period)
“Renter“ table (contains columns RENTER_ID, Last, First)
“Payment“ table (contains columns PAYMENT_ID, LEASE_ID, RENTER_ID, EMP_ID, Period, Date, Amount)



The “Admin” class  in the Cowboy Project Management system has methods for adding, viewing, updating, and deleting employee information. 
The Admin class has the following methods:
add_new_employee(db, last, first, position):(This method adds a new employee to the database)
lookup_employee(db, emp_id): (This method presents a current employee’s information)
update_employee(db, emp_id, new_position): (This method updates a current employee’s information)
delete_employee(db, emp_id): (This method deletes a former employee’s information from the database)


FINISH THIS SECTION ABOVE!


Employee class


Renter class


Ethics and Critical Thinking in Cowboy Project Management System
Ethics:
Ensure User Privacy: Ensuring the protection of individuals' personal data and privacy rights by implementing robust security measures and ethical data handling practices.
Respect User Preferences: Provide optional “opt-in” features that may improve accessibility of data to users.
Be Transparent: Be clear about what information is required and what it will be used for. Ensure the absence of dark patterns.
Ensuring Compliance: Adhering to legal and regulatory requirements, industry standards, and ethical guidelines to ensure ethical conduct and mitigate legal and reputational risks.
Critical Thinking
Identify Admin, Employee, and Renter Needs: Prior to building the system, we researched to identify and understand the needs the admin, employees, and renters would each have so we could tailor the system to fill those needs.
Improve User Experience: The Cowboy Project Management system is intuitive and free from errors to ensure users can focus on getting the right information rather than learning to use a program.
Ensure Accuracy: Information has been combed through for accuracy on availability of units, unit specifications, price, and periods of use. 
Our team’s goal was to design a project management system that enhanced the user experience through deliberate critical thinking while maintaining ethical standards.


