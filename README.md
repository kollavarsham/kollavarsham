kollavarsham
============

Meta repository that houses the API definition, algorithms, and links to all the other kollavarsham implementations

API draft
=========
Use Gregorian calendar Date and Time and find Malayalam Calendar Date and details about the star

API:
```
KollavarshamCalendar KollavarshamCalendar () //no args, to get a calendar instance for *now*
KollavarshamCalendar(int absTime) //absTime msecs since 1970 jan 1 00:00:00
KollavarshamCalendar(Calendar gregorianCalendar) // Calendar Object passed 
KollavarshamCalendar(String DateFormat, String Date) // Eg. ("dd/mm/yyyy", "13/09/1979") and all other formats supported by SimpleDateFormat
```
DatePicker widget type functionality?
```
Object KollavarshamCalendar{
  int absTime //absTime for the current Kollavarsham Calendar object
  String KollaVarsham //Year
  String Maasam //Month
  String thiyathi //Date
  String Nakshathram //Star
  Date fromGregorianCalendarDate //Start time of current nakshatram in Gregorian Calendar
  Date toGregorianCalendarDate  //End time of current nakshatram in Gregorian Calendar
  
  //Getters and Setters
}
```

