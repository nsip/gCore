
# gCore
Repository for Sharing information on the gCore Initiative

This initiative comes out of the A4L Strategic meetings held in Melbourne in December.
Initiated by Vendor members present.

All sentiments are in draft and available for feedback and comment.

	
Lightweight. Fast. Extendable. 

Need to move data quickly to or from a school or school district?
gCore Student and Staff represent the core details that need to be shared with applications 95% of the time. Simple and easy to understand they represent the basic elements to provision an application.
What is gStudentCore?
gStudentCore is a flat object that can be represented in JSON or XML. It consists of: GivenName, FamilyName, PreferredName, YearLevel


Optionally:
Gender - 
BirthDate - 
Email - 
Homegroup - 
LocalId - 
StateId - 
RefId 

What is gStaffCore?
gStaffCore represents the details of staff (teachers, administration staff) that need to be shared with an application. A flat object that can be represented in JSON or XML consisting of: GivenName, FamilyName, PreferredName, Title 


Optionally:
Phone - 
Email - 
LocalId - 
RefId 
Can I use this globally?
Yes! gCore is supported by all A4L locales and is consistent across the US, UK, AU and NZ. Given the objects represent the ‘core’ elements from region to region it is highly portable and will provides source systems and 3rd party applications with a globally consistent set of definitions for students and staff.
What if I need to share more data?
The 2 objects gStudentCore and gStaffCore are subsets of the rich A4L data model: In AU, StudentPersonal and StaffPersonal.  North America- xStudent, xStaff OR StudentPersonal and StaffPersonal.  UK – LearnerPersonal and StaffPersonal. Grow as needed!

