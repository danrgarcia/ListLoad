# ListLoad
Application for moving records between lists in Five9

Requirements to work correctly:

Application requires having a master list report created in Five9.
Details of report are:  
  * Folder Name: Shared Reports
  * Report Name: List Details

Report must have the following filters:
  * Columns slected in the following order:
    * first_name, last_name, number1, STATUS, number2, company
  * Critera:
    * List selected that will be the master list
    * Advanvced Filters:
      * STATUS equals New
      *  
