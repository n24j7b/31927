java c
31927 – Application   Development   with   .NET 
32998 -   .NET   Application   Development 
SPRING 2024 
ASSIGNMENT 1 – SPECIFICATION
Due date                                      Monday 23 September 2024, 11:00am
Demonstration                Required in the lab/tutorial session
Weight                                           35%
Groupwork                              Individual
Submission                              Complete project folder zip
Submit to                                   Canvas
Summary 
In this assignment, you are required to   model the dotnet   Hospital   Management   System   by developing   a   console application using   C#.The application should have appropriate data structures to   distinguish   between   a   Doctor, Administrator   and   Patient as well as store the necessary   links   between them   (such   as   an   appointment,   between   a   Doctor   and   a   Patient). You are given complete control in   how you   create these   data   structures,   but   guidance   has   been      given overpage.
Objects should be stored in the system   and   also written to   .txt   ﬁles   such   that   the   system   can   read   them   in   and   regenerate existing objects on load. This   is   mandatory.
Students will need to submit the complete project folder   in zip   format,   which   will   have   the   complete   C# code, solution ﬁle,   data ﬁle, etc.   required to run/test the   program. Any   special   instructions   required to   run   the code has to be provided   in   a text   ﬁle.   Submitting   a   lone “   .exe”   is   not   acceptable. 
Assignment Objectives: 
The purpose of this assignment is to demonstrate competence   in   the   following   skills:
•          Ensure ﬁrm understanding   of the   .NET framework,   C#   basics   and   C#   syntax
•          Understand how the   .NET framework   implements   OO   concepts   and the   implications   this   has   for   new language   design
•          Array   and   string   manipulation
•          Creating custom   classes   and   methods   in   C#
•          File   reading,   writing   and   manipulation   in   C#
•          Creating   interactive   console   applications
•            Creating good OO design.
Program and data 代 写31927 – Application Development with .NET 32998 - .NET Application Development SPRING 2024 ASSIGNMENT 1R
代做程序编程语言structures: 
•          How you structure the classes   in your   program   is your   choice.   One   thing   you   are   not   allowed   to   do   is make your program fully contained inside   Program.cs,   or   any   single   class.
•          In the dotnet   Hospital   Management   System,   a   user can   log   in   as   either   a   Patient,   a   Doctor,   or   an administrator. These are different roles, which would store different   information,   and would   have   a   different menu. Your code structure should   reﬂect this.
•          Additionally, your code will need to generate Appointments.   An   appointment would   need   a   reference   to a single   Doctor and a single   Patient; your code   structure   should   reﬂect this.   You   do   not   need   to manage   Dates/times for appointments   (or anywhere, for that matter)   in your code. This   may   result   in   appointments being difﬁcult to   distinguish and sort; you will   not   be   marked down   for   this. 
•          Every patient, doctor   and   admin,   has   a   unique   ID.   This   ID   should   be   an   integer   of   reasonable   length   (5-8 digits). This can be   randomly generated, or   incremental,   but   it should   be   generated   by the system on object creation, not chosen/inputted   by the   user.
Further recommendations: 
•          Objects will need to   be   printed out   one   by   one,   it’s   recommended that   each   data   structure   has   a   toString() function which compresses the   notable data of the class into   a succinct   line.
•          Each   role should be   its   own   class   and   it   should   have   its   own   MainMenu   method,   don’t   try   and   create   separate versions of the menu   in   Program.cs.
•          Don’t get confused   by Administrators.   Doctors   and   Patients   can’t   at   any   stage   have   “admin   privileges”; the administrator is a completely separate   entity.
•          You may ﬁnd it   useful to   abstract   common   functionality   into   its   own   class,   such   as   a   FileManager   class with static   read and write methods or a   Utils class   which   contains   the   methods   to   generate      ID’s and ﬁlter   lists.







         
加QQ：99515681  WX：codinghelp
