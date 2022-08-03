# Assessment questions

I] Add Employee Form

1. Create a form to save employee details Fields as
     - Personal Details:-    
   First Name,
     Last Name,
     Gender (radio),
     Phone number,
     Email,
     DOB (date field)
     - Qualification:-   
       Post Graduation(select), % (numeric textfield), University (autocomplete textfield),
       Graduation(select), %(numeric textfield), University (autocomplete textfield),
       HSC, %(numeric textfield), University (autocomplete textfield),
       SSC, %(numeric textfield), University (autocomplete textfield),
       Other(textfield)
     - Work Preference Location:-
     WFH,WFO,Hybrid (checkbox)
     Shift: 1st shift, 2nd shift, 3rd shift (select)
     Type of employment: Part time, Full Time, Weekends.
     Available on weekend: Toggle
     

2.Add proper validations on form and save the information to hive database. Every item saved should be uniquely identified. Also save created_on and update_on in the database and update accordingly on every update. After adding the same should reflect in the list on home page.



II] Home Page

1. Display list of employees from database.
2. Search form will have search field and check options of all fields in add employee form. User can enter in search field and check the items he has to search for. In case if any of the fields are not checked, check for all fields in database.
   If no results found display appropriate message.
3. Filter bottom sheet
   Filter results on the basis of all fields inside add employee form.
4. Sort bottom sheet
   Sort by last added, first added, first name, last name
5. Export
   Export results to excel sheet and option to share excel file via intent
6. Select
   Option to select, deselect, select all and deselect all.
7. Options
   After any item is selected, display option to delete, export, share (share as text)
8. Details
   On click of item, display information and option to edit.
9. Long Press
   View popup menu to edit and delete information. For delete, proceed after a confirmation popup.




