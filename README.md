# Assignment-6
This repository contains files for Assignment 6. 

1.It contains the binary database file.

2.It contains the images of the data present in the tables.

3.It contains the screenshots of the insert queries when invalid values are entered into the author table which are handled using Triggers. 

# Trigger Explanation 

Here the trigger to check the constraint on certifications is made. It is invoked before the INSERT operation on the Author table. It checks the NEW values of certifications before insert. If the inserted new values for certificatcertifications are not present in the list of valid values it raises an exception and an error message is displayed that 'Invalid value for certification'
