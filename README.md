# EscapeRoom
MTD2018: Usability and Interaction Design (mtd282)
<br><br>

To Clone Repository
--------------------------------------------------------------------------------------------------------------------
<ol>
	<li> Download GitHub Desktop on https://desktop.github.com/ and install</li><br>
	<ol>Go under File 
		<li>choose Options: and Login with your GitHub Account there</li>
		<li>choose Git: and enter your Name and Email adress</li>
		<li><Save changes/li>
	</ol>
	<li></li>
</ol>

1. Download GitHub Desktop on https://desktop.github.com/ and install<br><br>
2. Go under File  
    a. choose Options: and Login with your GitHub Account there<br>
    b. choose Git: and enter your Name and Email adress<br>
    c. Save changes<br><br>
3. Choose Clone a repository from Internet
    a. first choose your path to your local clone directory<br>
    b. then if the Repository is listed on the right side you can just choose that one<br>
    c. otherwise go to repository "EscapeRoom", click the button Clone or Download and copy the link listed there<br>
       https://github.com/Isa-git/EscapeRoom.git<br>
    d. and paste the Link into input field "Enter a repository URL..."<br><br>

    
 To Work with Unity
--------------------------------------------------------------------------------------------------------------------   
1. Open Project and edit Project Settings
    a. Edit - Project Settings<br>
    b. Under Editor Tab:<br>
    <ul>
	<li>Version Control - Mode: Visible Meta Files</li>
	<li>Asset Serialization - Mode: Force Text</li>
    </ul> <br><br>
2. edit Gitignore so it doesn't show and push meta files<br>
    a. open .gitignore File<br>
    b. delete / before the project fiels in the beginning - it should now be like: <br>
	&ensp;...<br>
	[Ll]ibrary/<br>
	[Tt]emp/<br>
	[Oo]bj/<br>
	[Bb]uild/<br>
	[Bb]uilds/<br>
	[Ll]ogs/<br>
	[Mm]emoryCaptures/<br>
	...<br>
    c. now the unnessessary meta files won't be pushed <br><br>
3. from now on you can commit the project normally
    a. choose commit changes<br>
    b. go to history and right beside the new commmit that is shown, press icon to upload to the git repository<br>
       or choose Push origin after the branch on top<br>
    c. to pull from repository <br>
       1. be sure to commit (without pushing) before pulling, if you made changes yourself (otherwise your changes will be gone)<br>
       2. after you pulled you can push your changes<br>
       3. if two people change the same file and line there will be some conflicts. be sure to fix them in github or afterwards in unity itself<br>
    d. Version Control: you can always reset a former stage through the version control in your git-repository<br><br>


First Person Exploration Kit Documentation
--------------------------------------------------------------------------------------------------------------------
http://whilefun.com/fpedocs/FPEKitDocumentation.html<br><br>


Tutorial Link for GitHub-Unity-Projects
--------------------------------------------------------------------------------------------------------------------
https://www.youtube.com/watch?v=qpXxcvS-g3g
