List Usecase
UC-01: Sign in
T1: Username must not be blank.
T2: Password must not be blank.
UC-02: Sign up
T3: Email: Email ID is not valid.
T4: Username must be from 3 to 20 characters.
T5: Password must be from 6 to 50 characters.
T6: Username - First character cannot have space.
T7: Username - has no spaces between characters.
T8:  Telephone Number  – Special character are not allowed.
T9:  Telephone Number  – Character are not allowed.
T10:  Telephone Number - First character can not have space.

UC-03: Forgot Password
T11: Forgot password - email is not vaild.
T53: Forgot password - email does not exist in the system.
T12: Forgot password - Confirmation Password must be the same as New Password.
UC-04: Search Services
T13: Search character not found.
Ex: “The services not found”
UC-05: View List of Services
UC-06: View Detail Service
UC-07: Sort Services
T14: Price - Sort by price from high to low
T15: Price - Sort by price from low to high
T16: Rating - Sort by high rating
T17: Rating  - Sort by low rating 	
T18: service - Sort by service
T19: Sort by combine sorting options
UC-08: View Profile
UC-09: Edit Profile
UC-10: Booking Service
T20:   Pet Type - Pet Type must be selected
T21:   Date - Date must be selected
T22:  Timeslot - Timeslot must be selected
T23:  Pet Name - Name must not be blank
T24:  Weight - Pet weight should only contain numbers
T25:  Weight - Pet weight should not contain special characters
T26:  Weight - Pet weight should not start with a space
UC-11: Cancel Booking
UC-12: View Booking Detail
UC-13: Feedback Service
T27: Feedback - Feedback must not be blank
T28: Star rating must be selected
T29: Feedback - Feedback must be input from 20 to 100
UC-14: Create New Service
T30: Name - Name must not be blank
T31: Description - Description must not be blank
T32: Tags - Tags must not be blank
T34: Date - Date must be in future
T35: Weight - Weight must not be blank
T36: Weight - Weight must be numeric
T37: Weight - Special character are not allowed
T38: Age - Age must be a numeric
T39: Age - Special character are not allowed
T40: Age - Age must not be blank
T41: Gender - Gender must not be blank
UC-15: Modify Service
T42: Service Name must not be blank
T43: Service Description must not be blank
T44: Tags must not be blank
T45: Pricing Table must have at least one valid entry
UC-16: Remove Service
UC-17: Check History Booking
UC-18: Accept/Cancel Booking
UC-19: Manage Availability (Time Slot)
UC-20: View Account List
T46: View list of successful accounts
T47: Empty account list
T48: Check the pagination of the account list
T49: Search for accounts in the list
T50: Filter account list by role
UC-21: View Account Detail
UC-22: Create Account
T38: Email: Email ID is not valid.
T39: Username must be from 3 to 20 characters.
T40: Password must be from 6 to 50 characters.
T41: User name – First character cannot have space
T42: Telephone Number  – Special character are not allowed
T43: Telephone Number  – Character are not allowed
T44: Telephone Number - First character can not have space
T45: RoleID - RoleID must be selected
UC-23: Modify Account
T46:  Email - Email is not valid
T47:  Email - First character can not have space
T48: Password must be from 6 to 50 characters.
T49:  Telephone Number  – Special character are not allowed
T50:  Telephone Number  – Character are not allowed
T51:  Telephone Number - First character can not have space
T52: RoleID - RoleID must be selected
UC-24: Delete Account
UC-25: Confirm Payment
T53: Method Payment - Method have to choose
T54: Name - Name must not be blank
T55: Name - Name must be valid
T56: Card Number - Card number must be valid
T57: Expiry Date - Expiry date must not be blank
T58: Expiry Date - Expiry date must be valid
T59: CVV - CVV must not be blank
T60: CVV - CVV must be valid

Phân công viết Test case
--------sping 1---------------
Nguyên UC 6,8
Bin UC 9,10
Phong UC 11
Minh UC 12
Hoàng UC 17
Hòa UC 25
---------Spring 2----------
Hòa UC 14
Hoàng Uc 15
Nguyên UC 16
Phong 18
Minh 19
--------Spring 3-----------
Hòa UC 20
Hoàng Uc 21
Phong UC 22
Bin 23
Minh 24
-------Spring 4-----------
Bin UC 1
Nguyên UC 2
Phong UC 3
Minh UC 4
Hoàng UC 5
Hòa UC 7,13

