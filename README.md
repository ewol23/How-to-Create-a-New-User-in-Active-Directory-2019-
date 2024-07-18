# How-to-Create-a-New-User-in-Active-Directory-2019-
How-to-Create-a-New-User-in-Active-Directory-2019
How to Create a New User in Active Directory 2019

Creating a new user in Active Directory (AD) on Windows Server 2019 involves a series of steps using the Active Directory Users and Computers (ADUC) console. This guide provides a detailed walkthrough of the process, supported by screenshots. Follow the steps below to create a new user.
Prerequisites

    (Ensure you have administrative privileges on the Windows Server 2019 machine
    (Active Directory Domain Services (AD DS) should be installed and configured.

Steps to Create a New User
Step 1: Open Active Directory Users and Computers

    Launch  Console:
        Open the Start menu and type Users and Computers, then press Enter. This command will open the Active Directory Users and Computers console.
        https://github.com/ewol23/How-to-Create-a-New-User-in-Active-Directory-2019-/blob/0745ce5619a120e782c1960f44402e0c11302640/unnamed-2.png 

Step 2: Navigate to the Desired Organizational Unit (OU)

    Expand the Domain (https://github.com/ewol23/How-to-Create-a-New-User-in-Active-Directory-2019-/assets/153697751/e00f36dc-125c-4a85-8851-7dd309472ff5) 

        In the left pane, expand your domain (mydomain.com in this example) to view the available Organizational Units (OUs).

    Select the OU:
        Choose the OU where you want to create the new user account. For example, select the Bankteam OU.

Step 3: Create a New User

    Initiate the User Creation:
        Right-click on the selected OU (Bankteam), hover over New, and then click on User.

Step 4: Enter User Information

    Enter User Details:
        Fill in the required details in the New Object - User dialog box:
            First name: Naira
            Last name: Clemson
            Full name: This will be auto-filled based on the first and last names.
            User logon name: NairaClemson

    Proceed to the Next Step:
        Click Next to continue.

Step 5: Set the User Password

    Set Password:
        Enter a password for the new user account and confirm it.
        Configure password options as needed (e.g., user must change password at next logon, password never expires, etc.).

    Complete the Creation:
        Click Next, review the details, and then click Finish to create the new user account.

Step 6: Verify the New User

    Verify the User in ADUC:
        Navigate back to the selected OU (Bankteam) and verify that the new user (Naira Clemson) appears in the list of objects.

Conclusion

By following these steps, you have successfully created a new user in Active Directory 2019. This process ensures that new user accounts are properly configured and managed within your organization.

Feel free to customize these instructions further to suit specific organizational needs or policies.
Additional Resources

    Microsoft Documentation on AD DS
