# :spider: Bugs

Below you can see some of the bugs I found on the projects I worked on Manual testing


----------------------------------
**Bug ID:** OHRM 154

**Title:**
Qualifications - License

**Description:** 
Qualifications - License - Check the License Number field if it does not only accept numbers

**Preconditions:** 

User has basic rights

**Steps to Reproduce:** 

1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
2. Log in with admin credentials
3. Go to My Info
4. Go to Qualification
5. Go to Licence subsection
6. Click Add button
7. Click on the License Type drop-down list and select "Microsoft Certified Systems Engineer (MCSE)" 
8. Insert "Numar Licenta@#$%^&"  in the License Number field

**Expected results:** 
The License Number field does not accept characters other than numbers.

**Actual results:**
The License Number field accepts characters other than numbers.

**Severity:** 
Low

**Priority:** 
Medium

**Environment:** 
Google Chrome Browser

**Bug data:** 
User: Admin & Pass: admin123

----------------------------------

**Bug ID:** OHRM 155

**Title:**
The "Japan" language is missing from Qualifications section

**Description:** 
My Info/ Qualifications/ The option "Japan" is not available as language

**Preconditions:** 

1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
2. Log in with admin credentials

**Steps to Reproduce:** 
1. Go to "My Info"
2. Click on "Qualifications" 
3. Scroll down until "Languages" and hit the "Add" button
4. Try to select "Japan" from the Language* droplist

**Expected results:** 
The japan language is displayed

**Actual results:** 
The japan language is not displayed and cannnot be selected

**Severity:** 
Low

**Priority:** 
Low

**Environment:** 
Safari

**Bug data:** 
User: Admin & Pass: admin123

