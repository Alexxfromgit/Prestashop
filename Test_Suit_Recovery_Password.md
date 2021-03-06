## Test case: 61073

**Summary:**
Checking the account password recovery on the site with valid data

**Preconditions:**

1. The password recovery page is open
2. The user is registered on the website
3. The user is not signed in on this website

**Step actions:**

1. Enter the correct email address in the email input field
2. Click on the retrieve password button
3. Check inbox of the entered email address
4. Go to the link from the confirmation email
5. Enter and confirm the new correct password
6. Check the sign in with the new password on the site

**Expected Results:**

1. The entered email is valid
2. The entered email is accepted
3. The confirmation email is been in the inbox of entered email address
4. Password recovery page is opened
5. The entered password is accepted
6. The sign in with the new password is accepted

**Importance:** Medium

**Requirements:** None

------------------------------------------------------------------------

## Test case: 61075

**Summary:**
Checking the account password recovery on the site with invalid data

**Preconditions:**

1. The password recovery page is open
2. The user is not signed in on this website

**Step actions:**

1. Enter only the letters in the email input field with consecutive 
   input of symbols "@" and "."
2. Click on the retrieve password button

**Expected Results:**

1. The entered email is invalid
2. The message about incorrect email address is shown

**Importance:** Medium

**Requirements:** None

------------------------------------------------------------------------
