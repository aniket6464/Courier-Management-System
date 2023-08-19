# Courier-Management-System
The Courier Management System is a PHP/MySQLi project that helps a courier company or businesses manage their customers’ parcels or packages details. The system stores all the branches or the company that can also be used when setting a destination where the recipient will pick up their packages or parcels. The system has a tracking feature where can help to monitor the movement of the customer’s parcel. 

The system has two types of user which is the Admin user and the Branch Staff user. The Admin user can manage all the data in the system, including managing the branches and branches staff user. The Branch user can only track a parcel and manage the list of packages where the origin or the destination of a parcel under the logged-in staff branch. The couriered items have multiple statuses, which are the “Item Accepted by Courier”, “Collected”, “Shipped”, “In-Transit”, “Arrived At Destination”, “Out for Delivery”, “Ready to Pickup”, “Delivered”, “Picked-up”, and “Unsuccessful Delivery Attempt”. These statuses will help to determine the movement of the parcel. The system also generates a report between two dates and selected quality. The couriered items of the clients can be set into “Deliver” and “Pickup.” The parcels marked as “Deliver” are the items to be delivered directly to the recipient.

In contrast, the “Pickup” will be delivered to the company’s branch near the recipient address. The system admin or staff user can store or adds multiple items at the same time. Still, these items will be held in the database separately because each package has a different reference number or different tracking number. For example, Client 1 has three boxes of the package to be couriered to the same recipient. The system user can submit the parcel registration to the system at once but will be stored separately to generate a different unique reference number to track each item quickly.

# Features of Courier Management System
Admin Side--
Login Page
	The page where the admin user submits their system credentials to access the admin side of the system.
Home Page
	The page where the admin user is being redirected by default after logging into the system. This page displays a summary of the data of the system.
New Branch Page
	The page where the admin submits the information on the new branch of the courier company.
List of Branches Page
	The page where all the branches of the courier company are listed and managed.
New Branch Staff Page
	The page where the system admin creates a new user for the specific branch of the company.
Branch Staff List Page 
	The page where all of the staff users of the system in all branches are listed and managed.

Both Users -
New Parcel Page
	The page where can system users submit the information of the parcels such as the sender and recipient details.
Parcel List Page
	The page where the parcels are listed and managed.
Parcel View Modal
	The page that shows the parcel’s details.
Track Parcel Page
	The page that displays the movement of the client’s packages or parcels.

Report Page
	The page where the printable list of the transaction of the courier company with the clients is listed.
