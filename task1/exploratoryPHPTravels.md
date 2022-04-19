Let's do Exploatory testing on [PHP Travels(Booking a stay in hotel)](https://www.phptravels.net/)

**Login Credentials**

_Email: user@phptravels.com_

_Password: demouser_

<br><br>
**[Exploration target_1]:** Booking details

**[Observations]:** 
1. When I click on "Confirm Booking" without filling the data, it should show red highlighted boxes instead of blue.
2. It should show error message to highlight missing fields in the form.
3. for booking confirmation, it should send verification mail to the user's mail id without direct confirming booking.
4. Email: It allowing me to take any random wrong domain name mail id: a@yahoo.cpm
5. Book hotel with max guests allowed (more than 2 adults and 2 children), it asking for the 2 adults and 2 children information
<br>


**[Improvements]:**
1. Red heighlights on missing field with error message
2. Without login, form should not allow me to enter "a@cpm". It should verify correct domain as well.
3. Form should accept numeric contact number with valid input data range.
4. The form should contain the fields to add more adults and more childs information in the form.

**[priority]:**  high

**[Risk]:** phpTravel will not have the correct data of the user if anything wrong happens

**[Risk Mitigation]:** Testing should start from requirement phase to vaoid these kinds of issues.

<br><br>


**[Exploration target_2]:** Multiple currency or Language, multiple payment options

**[Observations]:** Currently the form is only have currency USD and 
Language is English.

**[Improvements]:** The website should be displayed in multiple languages

**[priority]:**  medium

**[Risk]:** Number of users will be reduced.

**[Risk Mitigation]:** It should have discussed with Product owner

<br><br>

**[Exploration target_3]:** Hotel supplier connected

**[Observations]:** Booking engine pull the requested data from hotel's property management system (PMS) via API. As compared to other booking sites, less number of hotels are connected

**[Improvements]:** More hotel options should be displayed.

**[priority]:** - medium

**[Risk]:** If low number of choices will be available, number of users will be reduced.

**[Risk Mitigation]:** Discuss with Product owner and Manager to increase the hotel suppliers.

<br><br>

**[Exploration target_4]:** Pricing rules based on discounts and rates

**[Observations]:** Pricing rules based on discounts and rates and pulls extra services for cross-selling, and finally returns the information back to the user

**[Improvements]:** Tax rates should be shown on Booking details page

**[priority]:**  High

**[Risk]:** At payment page, tax rates are displaying so amount looks large and customer get distracted.

**[Risk Mitigation]:** Discuss with Product owner and developers.