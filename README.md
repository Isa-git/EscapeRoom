# EscapeRoom
MTD2018: Usability and Interaction Design (mtd282)


To Clone Repository
--------------------------------------------------------------------------------------------------------------------
1. Download GitHub Desktop on https://desktop.github.com/ and install
2. Go under File  
    a. choose Options: and Login with your GitHub Account there
    b. choose Git: and enter your Name and Email adress
    c. Save changes
3. Choose Clone a repository from Internet
    a. first choose your path to your local clone directory
    b. then if the Repository is listed on the right side you can just choose that one
    c. otherwise go to repository "EscapeRoom", click the button Clone or Download and copy the link listed there
       https://github.com/Isa-git/EscapeRoom.git
    d. and paste the Link into input field "Enter a repository URL..."

    
 To Work with Unity
--------------------------------------------------------------------------------------------------------------------   
1. Open Project and edit Project Settings
    a. Edit - Project Settings
    b. Under Editor Tab:
	1. Version Control - Mode: Visible Meta Files
	2. Asset Serialization - Mode: Force Text
2. edit Gitignore so it doesn't show and push meta files
    a. open .gitignore File
    b. delete / before the project fiels in the beginning - it should now be like: 
	[...]
	[Ll]ibrary/
	[Tt]emp/
	[Oo]bj/
	[Bb]uild/
	[Bb]uilds/
	[Ll]ogs/
	[Mm]emoryCaptures/
	[...]
    c. now the unnessessary meta files won't be pushed 
3. from now on you can commit the project normally
    a. choose commit changes
    b. go to history and right beside the new commmit that is shown, press icon to upload to the git repository
       or choose Push origin after the branch on top
    c. to pull from repository 
       - be sure to commit (without pushing) before pulling, if you made changes yourself (otherwise your changes will be gone)
       - after you pulled you can push your changes
       - if two people change the same file and line there will be some conflicts. be sure to fix them in github or afterwards in unity itself
    d. Version Control: you can always reset a former stage through the version control in your git-repository


First Person Exploration Kit Documentation
--------------------------------------------------------------------------------------------------------------------
http://whilefun.com/fpedocs/FPEKitDocumentation.html


Tutorial Link for GitHub-Unity-Projects
--------------------------------------------------------------------------------------------------------------------
https://www.youtube.com/watch?v=qpXxcvS-g3g
