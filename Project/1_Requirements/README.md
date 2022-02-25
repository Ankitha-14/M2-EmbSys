# Description
Biometric fingerprint devices are used in electronic balloters to identify voters. It is a fingerprint-based voting device that does not require the user to carry an ID card, including the required ID card. People in the polling booth can capture the fingerprints of voters in the field by simply placing their finger on the device. This acts as an ID.
 This data is  passed to the control unit for  checks. Controller  retrieves data from the reader and compares this  data with  existing data stored in during voter registration. If the data matches previously stored information Of the registered fingerprints, that person can cast  votes. Otherwise, a warning message will be displayed on the LCD and  votes will be prohibited. Voting is run manually using the push button. LCD is used to display results of related messages, warnings, and  results.
# High Level Requirements

|ID |	Description|
|-------|-----------------------------------------|
|HR01|It should be able to take input from the user|
|HR02|It should detect any finger print|
|HR03|It should be able to do functions like Enroll, Detect, Increment and Decrement finger-print data.|


# Low Level Requirements

|ID |	Description|
|---------|---------------------------------|
|LR01|If the user wants to Enroll press key “1”|
|LR02|If the user wants to reset or delete data from EEPROM press key “2”|
|LR03|If the user wants to decrement or increment the data press key “3” and “4”|
|LR04|User may download the attendance data by pressing and holding key 4

# Applications

*  It can be used in small elections such as: Fast track voting.
 
 * Can be used to conduct  polls at the Annual Meeting.
