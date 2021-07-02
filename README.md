# امانت گرفتن کتاب از کتابخانه

## **:سناریو**

### 1.  .شخص وارد برنامه میشود
### 2.  :اگر شخص عضو کتابخانه بود
 - الف).  شخص شماره عضویت و رمز عبورخود را وارد میکند  
 - ب).  لیستی از کتابها برای شخص نمایش داده میشود و شخص کتاب مورد نظرخود را در صورت وجود رزرو میکند
 - ج).  پیغام برای دریافت کتاب به کتابخانه مراجعه فرمایید برای شخص نمایش داده میشود

### 3.  :اگر شخص عضو کتابخانه نبود
- الف).  یک صفحه برای شخص باز میشود و شخص اگر مایل به عضویت بود مشخصات خود را شامل نام , نام خانوادگی , شماره ملی ,  شماره تلفن و ایمیل را وارد میکند
- ب). شخص  یک رمز عبور وارد میکند
- ج).  اگر ثبت نام با موفقیت انجام شد یک شماره عضویت به شخص تعلق میگیرد
- د).  شخص پس از تکمیل ثبت نام می تواند برای پرداخت هزینه ثبت نام به کتابخانه مراجعه کند
- ه). شخص دریافت کارت عضویت به کتابخانه مراجعه کند
- چ).  پس از طی تمامی مراحل شخص می تواند در برنامه درحواست رزرو کتاب خود را ثبت کند   


## **Scenario:** 
### 1. The person enters the program.
### 2. If the person is a member of the library: 
-  A) Enter the membership number and password.
-  B) Reserves the book if it's available.
-  C) The message "Please refer to the library to receive the book" is displayed. 
### 3. If the person is not a member:
-  A) Enter details including first name, last name, national number, phone number and email. 
-  B) Enter a password and pay the registration fee.
-  C) If the registration is successful   a membership number will be awarded the person. 
-  D) After completing the registration, person can request the book of his choice.


## **Functional requirements:**
-  1). Information about the current situation or the non-existence of books
-  2). Information on books set by members
-  3). Ability to search for books by name or author
-  4). The library in the system is accurate
-  5). Calculate and inform the remaining deadline book delivery for members
-  6). Ability to register new members in the system
-  7). Build a membership card for new registrations
-  8). Permit from the loan after the expiration of the membership card
-  9). It is possible to renew the membership for former members
-  10). Reading competitions
-  11). Ability to add new books and donation books to inventory
    
#### Non-Functional Requirements:
#### 1). operational
- The system is Desktop-based
- The membership number is the national code by default
#### 2). Cultural
- The system is in Persian
- Existence of solar date in the header of all pages
#### 3). Performance
-  Book search speed and book booking speed should be high
#### 4). Security
- Back up the information of all users and books every month

[Activity Diagrams](https://github.com/hossein-se/my-project/tree/main/documentation/Activity)
                                                                                                                         
