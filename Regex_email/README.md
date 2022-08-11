# REGEX EMAIL VALIDATION

Check if user entered email is valid using regex.
If valid return asterisked domain name with TLD visible
If not, show error message and ask to try again.

## Valid emails
andupu4@gmail.com   ---> *******@gmail.com              
vari4@gmail.com     ---> *****@gmail.com              
tola_55@yahoo.uk    ---> *******@yahoo.uk               
ada@go-goroll.net   ---> ***@go-goroll.net         
ada@ba.edu.ng       ---> ***@ba.edu.ng                
ada@gmail.com       ---> ***@gmail.com
adaeze_ndupu@ey.edu.ng    ---> ************@ey.edu.ng

## Invalid emails
ada@tol-a.gbg.ng_
ada.tola@yahoo.co.
ada_@yahoo.com
@y.com
tola@@co.com
45@r.c
a.@yahoo.com
ada_t@go.co..y
ada@5gmail.com
ada@trf.co$