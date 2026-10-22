# Project Specifications

## Feature 1.0: [Signup/Registration]

### 1.1 Overview

Allow user to registered himself on the system as a trusted entity to perform authorized tasks.  
There will be following types of registered users:

1. **Super:** For top level management
2. **Admin:** Manages operations like review and approval of discussions, comments and reports on them.
3. **Standard:** Use the system to get analysis or engage in discussions

### 1.2 Behavior
1. **Super** user will be hard coded.
2. **Admin** user will be created and manged by `Super` user
3. **Standard** user will have following ways to register himself.  
   1.  Email and password
   2.  Google

### 1.3 Email and Password based signup
1. User will provide email and password along with other user details.
2. System will verify email ownership by sending an OTP and verification link. User can choose any option.
3. User will be registered after successful verification

### 1.4 Google based signup
1. User will be authenticated using google.
2. Google will provide user email and other details.
3. Confirm or change user details other than email
4. Finally register the user

### 1.5 Designing
1. Maintain user statuses if mail is confirmed or not and details are provided or not and registration is completed or not.
2. Make sure same user can't be registered multiple time.
3. Allow setting up password also when user is onboarded with third party
4. Save how the user was registered at first.