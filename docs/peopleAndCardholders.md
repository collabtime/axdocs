### People & Cardholders
Records can be added to the system to log personal information, assign cards for door access, promote
user administrators, as well as print badges. Additionally, intrusion arm/disarm permissions can be
established within the single-entry point. People can exist in the system as individual people with no card 
assignments or access levels. For this reason, adding a card assignment or an access level is not required.

It is possible to add cardholders to the system by:

1. Select New – allows one person at a time to be added to the system. 
2. Batch Import – allows for groups of people to be imported through a CSV file format.
3. Active Directory Integration – Automated and synchronized database management.
Adding a New Person:
1. Select the ‘Access Control’ Tab.
2. Select the “New” button.
3. Enter First Name.
4. Enter Last Name.
5. (OPTIONAL)Choose a Badge Type.
6. (OPTIONAL) Complete additional 
fields.
7. Click “Save” or “Save & Close”.

** You can also select “Add Person” from 
the people list.

** Be sure to verify that the user was created using the "Event History" tab.

For Address Information is it possible to 
capture multiple addresses, numbers, and 
email addresses. Phone numbers must be 
added with a country code. For the USA and Canada that will look like '+1 333-444-5555'. The phone number 
can be added with '00', '+' or '1'.

When the Mass Messaging portion of Access Expert is being used it is also possible to specifically exclude a 
number or email address from being used by the system by click on the shield icon next to the address. This 
button will mark an address as private and prevent all future messages from going to that address. An address 
will also automatically be marked as private if the message fails to send.

During the entry of the Person Information, it is possible to:

1. Pre-Select the Badge Type.
2. Assign Access Levels.
3. Set Arm/Disarm codes and area permissions (when integrated with Bosch Alarm Panels).

To delete a cardholder, click the “Delete” button in the bottom right. This will remove the cardholder (and 
associated user) from the system and controllers.

### Card Assignments Tab:

Cards are added to a person’s record from the Card Assignments tab. It is possible for an individual person to 
have multiple access cards where each one has unique starting and ending times. Access Expert also tracks all
previously assigned cards.

Cards can also be set as Inactive by clicking the Green check box, thereby changing the icon to a red x, and then 
pressing “Save” or “Save & Close” at the bottom. This keeps the card number assigned to the card holder but 
will disable any access rights for the card. This is a toggle function, so a card set as de-active can be changed to 
active status by clicking the same button. This feature is useful for temporarily misplaced cards.

Cards that have expired will show in the Previously Assigned Cards section. These cards are no longer assigned 
to the individual and are available to be re-assigned to another card holder. Clicking the Red X on the left of a 
card assignment and clicking “Save” or “Save &Close” will expire a card.

How to assign a card:

1. Select the ‘Card Assignment’ Tab.
2. Click the “Add Card Assignment” button.
3. Enter the Displayed Card Number from the back of the card (note the Encoded Card field will 
automatically populate).
4. (OPTIONAL) Click on the PIN icon to add a PIN.
5. (OPTIONAL) Modify the Expires on Date as needed.
6. (OPTIONAL) Select the other optional card holder attributes.
7. Click “Save” or “Save & Close”.

How to assign a PIN:

1. Click the PIN image.
2. Manually enter the desired PIN number or Select 
Generate PIN and Access Expert will automatically 
generate a PIN assignment.
3. Click OK.

***Note: PIN numbers can only be assigned with a card assignment.

Other attributes include:

1. Anti-Passback Exempt – used when the cardholder is exempt from anti-passback controls.
2. PIN Exempt – Removes the requirement for the cardholder to enter a PIN when PIN is activated.
3. Extended Access – Door activation time will be the “Extended Grant Access Time” as configured on the 
reader.
4. Manager Level – Established a hierarchy for allowing cardholders to perform special functions.
5. Hex Value – Used when deploying Allegion Control locks only.

### Badge Preview Tab:

Badges are determined from the Person Information tab and can be used to pre-determine an Access Level.

From the Badge Preview tab, the operator can review the 
badge front and back sides prior to printing.
Since a person can have multiple badges, it is important to 
choose the right badge to be printed. For this screen, the 
badge is not modified as the intent is to provide the ability 
to print and preview. Once the card has been reviewed 
and the card has been selected the operator can then 
select the Print button which will then open the Windows
OS Printing window.

Access Expert uses standard Windows printer drivers. All 
printers supported by Windows are therefore useable
with Access Expert. 

***Note: Winows 8.1 and newer use a different OS
architecture than previous verions of Windows. Printing will not work on earlier versions of Windows.

### Account Tab
Persons can exist in the system with no access cards or access levels and they can also exist in the system solely 
as an operator. Operators are persons that can log into the system to perform administrative type functions.

To Add an Account:

1. Click on the ‘Account’ tab.
2. Enter a unique username.
3. Enter a password then Confirm the 
password.
4. Assign a Group.
5. (OPTIONAL) Adjust other User 
Settings.
6. (OPTIONAL) Adjust User Password 
Policy.
7. Click “Save” or “Save & Close”.

***Note: for a person to exist in the system as 
an operator they must have a valid email 
address entered in the Person Information Tab.

This will allow Access Expert to automatically send the login information to the user as well as instructions for 
installing the Windows Application.

The User Group assigned to the user will dictate what permissions the user has within the system. If no user group 
is assigned, a warning box will pop up indicating no permissions have been assigned. This user will be unable to 
log in until permissions have been assigned. 

See Users Section and User Groups Section for more information. 

### Custom Data Tab
Custom Data is a powerful feature in Access Expert that allows customers to capture vast amounts of data. The 
layout of the Custom Data tab is fully customizable. The creation of the forms will be addressed in Custom Forms
section of this document.

Information for this tab can be manually 
entered on the Person Page, imported during 
a batch CSV import or it can be automatically 
imported through the Active Directory 
integration.
For more information, see the Custom Forms
section.
