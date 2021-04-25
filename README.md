# Railway-Booking-Management
Steps to run the program on your local machine.
1. Download and configure MySQL Community Server(version 5 and above). Do not set root password for the server.
2. Create a Database named "test" and then run the following commands.

Create table user
(id char(20),
pass char(20));

insert into user values('admin','admin');

Create table ticket
(ticket_no char(40),
train_no char(40),
name char(40),
phoneno char(40),
age char(40),
gender char(40),
date date,
charge int(10));

Create table train
(train_no char(40),
train_name char(40),
from_place char(40),
to_place char(40),
depature char(40),
rent int(10),
seats int(10));

3. Open the project in Netbeans and resolve the problem by selecting mysql-connector-java-5.1.23-bin. The file location will be C:\Program Files (x86)\NetBeans 8.2\ide\modules\ext
4. Run the Welcome file.
