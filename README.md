# FileHideSecure
The File Hiding System with Secure Access and User Management is a Java-based project that provides users with a secure and efficient way to safeguard their files. This application emphasizes privacy and data security by allowing users to hide files in a MySQL database, implementing multi-factor authentication through email OTP verification.

Key Features
> File Hiding and Retrieval: Users can securely hide files within a centralized MySQL database. Files are encrypted to prevent unauthorized access, and can be retrieved and decrypted whenever needed.
> User Authentication and Management: Supports multiple user accounts, ensuring that only authorized users can access their hidden files through robust authentication mechanisms.
> Email OTP Verification: During signup and login, users receive OTPs via email for verification, adding an extra layer of security.
> User-Friendly Interface: The command-line interface is intuitive and easy to navigate, making the signup, login, and file management processes straightforward.
> Efficient Data Management: Seamless integration of Java with MySQL ensures efficient data storage and retrieval.
Tech Stack
> Java: The core language used for implementing the application logic.
> JDBC (Java Database Connectivity): Used to connect and interact with the MySQL database.
> MySQL: The relational database system used to securely store user information and hidden files.
> JavaMail API: Used for sending OTPs to users' email addresses for verification during signup and login.
> DAO Pattern: Data Access Object pattern used for managing interactions with the database.
> File I/O: Java’s file handling mechanisms are used for hiding and retrieving files.
Usage
1. Signup:
  > New users can sign up using their email IDs.
  > An OTP will be sent to the provided email for verification.
  > Upon successful OTP verification, the user is registered in the system.
2. Login:
  > Users can log in with their registered email.
  > An OTP will be sent to the email for verification.
  > Upon successful verification, users can access the file hiding and
  retrieval functionalities.
3. File Hiding:
  > Users can select files from their local system and hide them within the   system's database.
  > Files are encrypted and stored securely in the database.
4. File Retrieval:
  > Users can retrieve their hidden files at any time.
  > The files are decrypted and restored to their original form.
5. Profile Management:
  > Users can update their profile details and manage hidden files from the   user dashboard.
