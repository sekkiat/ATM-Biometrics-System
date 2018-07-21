# ATM System with Multi Biometrics

The fingerprint and face recognition will be implemented in the ATM system to increase the security.

## Feasibility studies

As we all know, in these recent years, there are many robbery cases happen at the ATM machine where the robbers will attack the 
victim when they are doing withdrawals or other transactions. The number of this cases has been increasing rapidly.
In addition, recently, there are several RFID theft scanning cases where the thieves will use a RFID reader to
copy the information of the victim‟s credit or debit card and perform illegal transactions without the victim's
knowledge. Therefore, by implementing biometrics at the ATM machine could reduce the
number the cases mentioned above and people can have a safer and peaceful living.

## Prerequisite

- U.are.U4500 USB Finger Print Reader

### Libraries

- OpenCV - open source library to carry out face recognition and enrollment
- DigitalPersonal - proprietary library to carry out fingerprint recognition and enrollment

## Implementation

The ATM system with multi biometrics seperate to two parts:-

- Java application - the main system that carry out the login,
register and fingerprint enrollment and recognition to the user based on Java by using IntelliJ IDEA.

- Visual Studio application - carry out the face enrollment and recognition to the user based on C# by using Visual Studio.

#### **Due to the occasion, I'm not able to upload my Java Application (fingerprint biometrics).Therefore, This project only available in Visual Studio Application (face biometrics).** 

## Process

- Main Menu 

Since we did not have the real ATM machine, reader, card and so on. Our system will ask the user to login or register in the main menu.

- Register (Fingerprint Enrollment)

Users required to enter their name to register ATM card. After that, the system will auto generate a 16-digit ATM number for the user and require user to enroll their 5-finger fingerprint. Each finger require 4 times scanning.

![first](https://scontent.fkul14-1.fna.fbcdn.net/v/t1.15752-9/37536285_10212437757243215_2514183012225122304_n.png?_nc_cat=0&oh=7ec3122535e55b7ca72b39683a05e093&oe=5BD843E3)

- Register (Face Enrollment)

User required to face the webcam to carry out the face recognition enrollment. The face of the user will cover by a red rectangle if the face detected.

![first](https://scontent.fkul14-1.fna.fbcdn.net/v/t1.15752-9/37537822_10212437850685551_7623939766446194688_n.png?_nc_cat=0&oh=3956506a18584d4bc0e7b148d6e9c2f9&oe=5BCBD34D)

- Database

Information will saved into database such as name, card number, and encryted fingerprint templates of each finger.

![first](https://scontent.fkul14-1.fna.fbcdn.net/v/t1.15752-9/37646158_10212437855245665_107716993804664832_n.png?_nc_cat=0&oh=f7301cee86280c221fe7c856aa242846&oe=5BD6AB2E)

For the face, it will save into a image folder.

![first](https://scontent.fkul14-1.fna.fbcdn.net/v/t1.15752-9/37588071_10212437880046285_5986863662466334720_n.png?_nc_cat=0&oh=356da66056700b1fa324e119cf495600&oe=5BD871EC)

- Login (Fingerprint Rcognition)

In the login, user required to enter their card number to check whether the user is valid or not. If the card number is valid,
system asks the user to scan their 5-finger fingerprint to do the fingerprint recognition before entering the system.

![first](https://scontent.fkul14-1.fna.fbcdn.net/v/t1.15752-9/37425279_10212437856365693_2984577300885929984_n.png?_nc_cat=0&oh=6d72ea00c18223e83136518c10de4dc2&oe=5BCA3B9E)

- Login (Face Rcognition)

Before proceed any further, user required to face the webcam to carry out face recognition.

![first](https://scontent.fkul14-1.fna.fbcdn.net/v/t1.15752-9/37603562_10212437860525797_6735161439192875008_n.png?_nc_cat=0&oh=9840606f23d00244dd51e3ce45bf5770&oe=5BC55645)

- Process completed 

Now, the user is authorized by the system. Therefore, the user is able to process withdraw, transaction and check balance etc.
