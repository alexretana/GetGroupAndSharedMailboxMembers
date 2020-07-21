# GetGroupAndSharedMailboxMembers

This is a powershell script that utilzes the Azure AD module to create a list of members for every group and every share mailbox in an organization into two seperate CSV files.

### Tutorial:

After cloning the directory, right click the file from the file explorer of your choice or run it directly from a powershell cmd line.

![RunPowershellScript](https://github.com/alexretana/GetGroupAndSharedMailboxMembers/blob/master/Images/RunPowershellScript.PNG)

It may ask to change the Execution Policy, which you can respond with "[A] Yes to All"

![ExecutionPolicyYesToAll](https://github.com/alexretana/GetGroupAndSharedMailboxMembers/blob/master/Images/ExecutionPolicyYesToAll.PNG)

It will prompt you to login using an admin email account.

![AdminLogIn](https://github.com/alexretana/GetGroupAndSharedMailboxMembers/blob/master/Images/AdminLogIn.PNG)

Then allow for several minutes for this to run depending on the size of the organization. Finally two new excels with date in the name will appear. Running the script twice in the same day will overwrite the files.

![FinalProduct](https://github.com/alexretana/GetGroupAndSharedMailboxMembers/blob/master/Images/FinalProduct.PNG)

By using pivot tables, it will be easy to group the information by users or groups/shared mailboxes.
