# Graduation_Project_SBS
Out of our love for our homeland, Palestine, we thought of a project that works to alleviate
the suffering of the Palestinian people in the registration process for visiting prisoners in the
occupation prisons, in addition to facilitating the process of coordinating visits programs for
the International Committee of the Red Cross.
So this project is about creating a mobile application used by the families of prisoners who
want to arrange a visit for them, and thus the application facilitates the process of booking
visits for families and facilitates their communication using a direct chat with the International
Committee of the Red Cross, the families being able of booking a visit through a page that
contain the available visits in the during the month. They can click on the appropriate visit for
them and see detailed information about it, also, there will be a reservation button for booking
a visit, or they can inquire about the visit by pressing the query button, which allows sending
an email. And the system will also provide certificates or paper proof needed by users, the
user can choose the specific certificates they need such as a visit permit or arrest certificate,
also, the user will be able to download them as PDF files to print them later, in the mobile
application there’s will be a part of the real-time chat to communication between prisoners
families, so using it they can contact reassure each other and talk about news together, also,
there’s will be part to the latest news about the prisoners that is published by the staff in Red
Cross. In addition, the project will contain a web portal for the staff of the Red Cross who deal
with prisoners and prisoners’ families, this portal enables them to coordinate visit programs for
the families of prisoners, as it contains complete data for prisoners, their families, and prisons,
which helps in organizing the process of coordinating visits, it enables them to communicate
with the families of prisoners easily by the direct chat, also the portal will support real-time
notification in case if there’s any change in the visit it will send to all visitors in this day and
if there is no respond from the user the staff will call to them, and the system will also provide
certificates or papers Proof needed by the staff like health insurance and there’s the ability to
print them, also, the staff can publish the latest news about the prisoners. As a result, this
project will facilitate faster communication between the International Committee of the Red
Cross and the families of the prisoners than the traditional methods.
React Native and Node.JS are the programming languages that we will use to write the application and website. Also, we will use SQLite and DB at the backend. As a result, this project
will cover all the needs of prisoners’ families and provide them with services easily, in addition
to that it will be a new version of the traditional method used by the Red Cross in tracking
the conditions of prisoners and communicating with their families.

...................................................................................................................................................................................................................................................................................................
The login page features two input fields for entering the email and password, along with a
”Login” button. It is worth noting that each user of the system has a unique email. In case
the employee does not have an account, they can click on the ”Sign Up” button to create one.

![1](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/5bb6fd55-a218-4056-bc8b-c5565319d292)

The signup page is accessed by the user if they haven’t registered in the system before. They
need to enter their name, location, profile picture, email, and password. Upon clicking the ”Sign
Up” button, they will be successfully registered in the system, given that the email is unique.
It is worth mentioning that all fields are required except for the profile picture. Additionally,
the page also contains a ”Log In” button for users who already have an existing account.
It should be noted that both the signup and login pages are responsive, meaning that the position of the components within them adjusts according to the screen size to ensure compatibility
with all screen sizes.

![2](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/beed7847-0d7c-4bfd-a582-84f5f54f5341)

The personal profile page displays information about the employee, including their personal
details and the posts they have published

![3](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/07bb8237-a598-411f-9e57-4db1adcca0e2)

The homepage, which is displayed after logging in, allows the employee to publish posts and view
all the posts in the system. Additionally, it features a monthly calendar and a top navigation
bar that displays notifications regarding visitor registrations and emergency messages.

![4](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/579c051c-697a-4d65-bc5c-6a5a09e816c6)

The chat page displays previous conversations and allows the user to create new conversations.
It includes a chat area where specific chat messages are displayed, enabling the user to send text
and image messages within the conversation. The page also shows the participants involved in
the conversation and includes an option to display images within the chat. Additionally, there
is an option to delete the conversation.

![5](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/f50a8b0d-9779-48d7-955c-5e637c814746)

The visitors’ information table page displays a table with visitor data in the system, including
name, picture, visitor’s associated prisoner ID, and more. Each row in the table contains three
icons: one for displaying detailed information, another for editing the row’s data, and the third
for deleting the visitor from the system. Additionally, the page includes three top buttons for
downloading the table as a PDF, printing it, or adding a visitor to the system.
Furthermore, the page includes an input field where the desired search data can be entered,
and the table is filtered based on the input.


![6](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/f8499ec5-7d42-43ea-b0c0-2c17678fb557)

The visitor registration page allows the employee to request visitor information and register
them in the system. Once registered, the visitor gains access to the application and can register for visits. It is important to note that the ID is unique and that an email is required.
Additionally, the visitor must have a corresponding prisoner in the system to be accepted for
registration. All fields are mandatory, except for the photo and VisitID.

![7](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/1205b5bc-57d3-473d-bbcc-42ab5d8ad0d8)

The Visitor Details page provides detailed information about the visitor. It displays the associated prisoner’s data, including their place of confinement. It also shows the recorded visit and
its details. Additionally, the page includes two buttons: one to return to the table and another
to access the visitor’s information editing page. 

![8](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/d1d7fbb3-b0c3-4b8a-a249-aa8e9714a159)

When the ”Print” button is clicked on the page, it triggers the printing functionality for the
table

![9](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/0fda5fd1-d0a9-421e-9383-523ae0bb668a)


![10](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/f6ebb787-7f12-4fad-a6ab-8c832ec468ca)
![11](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/de7dcfd4-a801-41af-9ab4-4ded192ffc6b)
![12](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/0baed28d-8e98-4bb3-b98d-945c2784b364)
![13](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/b14e3643-51ec-4693-b41b-0b2c587574f3)

The emergency messaging service page in the system contains three fields: subject, visitor ID,
and location, along with a button to send the notification. Additionally, the page displays a list
of all emergency messages previously sent by visitors. These messages include sender details,
message subjects, content, and timestamps. This feature facilitates direct communication between International Committee employees and visitors, enabling efficient handling of emergency
situations and important updates.

![14](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/8d7abf3d-7c1e-47ee-b809-ebd899efee30)
![15](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/d041c7e4-dc91-452f-9d46-9d9e09010e3e)
![16](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/4c050b39-be97-48ef-b4cd-63303215429c)

The permit issuance page allows the entry of a specific visit ID, and upon clicking the ” Generate
Permit Form ” button, all permits for the registered visitors on that visit are generated. By
clicking the ”Download PDF” button, all the permits are compiled into a PDF file, which can
be downloaded and printed.

![17](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/b12e8be2-be27-40a0-85ba-9f3bf196d367)
![18](https://github.com/sojodjamous/Graduation_Project_SBS/assets/107058107/14464902-af28-4573-b2f1-852231fe4a0c)
