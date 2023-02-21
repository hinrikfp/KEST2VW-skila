## Lab - Bitlocker and Bitlocker To Go

### Why is it important to save a BitLocker recovery key?
ef maður gleymir lykilorðinu

### What is the function of a TPM in relation to BitLocker?
TPM athugar hvort það er búið að breyta vélbúnaði og geymir dulmálslykla
| Policy | Security Setting |
| -- | -- |
| Enforce password history | 8 |
| Maximum password age | 90 dagar |
| Minimum password age | 1 |
| Minimum password length | 8 |
| Password must meet complexity requirements | enabled |
| Store passwords using reversible encryption | disabled |

### According to the security policy in Step 1, how many times is a user allowed to attempt to login before the account is locked?
5

### How long should the user have to wait before attempting to log back in?
5 Mínútur

### Are there any you would recommend changing? Why?
"access this computer from the network" ef maður vill stoppa eða leyfa fólki að skrá inn frá netinu

| Policy | Security Setting |
| Interactive logon: Machine inactivity limit | 1800 |
| Interactive logon: Prompt user to change password before expiration | 7 |
| Interactive logon: Message text for users attempting to log on | Your activity is monitored. This computer is for business use only. |
| Interactive logon: Message title for users attempting to log on | Caution. |

## Lab – Configure Users and Groups in Windows

### What are the names of the accounts listed?
Administrator, DefaultAccount, ding, dong, Gues, linus, Numi-Hinrik, WDAGUtility

### Select the Groups folder. Name five groups from the list.
Administrators, Users, Guests, Power Users, Remote Desktop Users

### Which group does your account belong to?
Administrators

### What is Student01 required to do when logging in the first time?
hann mun þurfa að breyta lykilorðinu sínu

### What group does Student01 belong to?
Users

### From the description, can the members of the Users group make system wide changes? What can the Users group do on the computer?
notendur í Users hópinum geta ekki breytt kerfinu en geta samt notað flest forrit

### Who are the group members?
ding, dong , linus, nemandi, student01

### Were you successful in creating the new account? Explain.
Nei, maður þarf Administrator réttindi

### Were you able to navigate to www.cisco.com?
já

### With the group ITEStaff highlighted, what can the members do in this folder?
Lesa og framkvæma

### Were you successful?
já

### Were you successful?
nei vantar réttindi fyrir Staff möppuna

### Navigate to C:\. Can you place a text file in the Staff folder? 
Nei Student01 hefur ekki réttindi til að far ´i Staff möppuna

### Are you able to access the content in the Student01 and Student02 folders? Explain.
Maður hefur ekki aðgang að Student01 möppuni en hefur samt aðgnang að Student02 möppuni

### Were you able to access the content in the folders Staff, Student\Student01 and Student\Student02? Explain.
Staff01 hefur aðgnang að student möppunum

### Can you log on as Staff02? Explain
nei, Staff02 birtist ekki þar sem maður velur notanda

### How would you give administrative privileges on the local computer to all the members of ITEStaff?
Setja þá í administrator hópinn

### How would you deny access to a file for everyone except the owner?
breyta réttinda stillingarnar til að bara notandin hafi aðgang





