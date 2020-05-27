# EscapeRoom
MTD2018: Usability and Interaction Design (mtd282)
<br><br>

To Clone Repository
--------------------------------------------------------------------------------------------------------------------
<ol>
	<li> Download GitHub Desktop on https://desktop.github.com/ and install</li><br>
	<li>Go under File</li>
	<ol>
		<li>choose Options: and Login with your GitHub Account there</li>
		<li>choose Git: and enter your Name and Email adress</li>
		<li>Save changes</li>
	</ol><br>
	<li>Choose Clone a repository from Internet</li>
	<ol>
		<li>first choose your path to your local clone directory</li>
		<li>then if the Repository is listed on the right side you can just choose that one</li>
		<li>otherwise go to repository "EscapeRoom", click the button Clone or Download and copy the link listed there<br>
      	 	    https://github.com/Isa-git/EscapeRoom.git</li>
	</ol>
</ol><br>

    
 To Work with Unity
--------------------------------------------------------------------------------------------------------------------   
<ol>
	<li>Open Project and edit Project Settings</li>
	<ol>
		<li>Edit - Project Settings</li>
		<li>Under Editor Tab:</li>
		<ol>
			<li>Version Control - Mode: Visible Meta Files</li>
			<li>Asset Serialization - Mode: Force Text</li>
		</ol>
	</ol><br>
	<li>edit Gitignore so it doesn't show and push meta files</li>
	<ol>
		<li>open .gitignore File</li>
		<li>delete / before the project fiels in the beginning - it should now be like:</li>
		<ol>
			...<br>
			[Ll]ibrary/<br>
			[Tt]emp/<br>
			[Oo]bj/<br>
			[Bb]uild/<br>
			[Bb]uilds/<br>
			[Ll]ogs/<br>
			[Mm]emoryCaptures/<br>
			...
		</ol>
		<li>now the unnessessary meta files won't be pushed</li>
	</ol><br>
	<li>from now on you can commit the project normally</li>
	<ol>
		<li>choose commit changes</li>
		<li>go to history and right beside the new commmit that is shown, press icon to upload to the git repository<br>
       		    or choose Push origin after the branch on top<br></li>
		<li>to pull from repository </li>
		<ol>
			<li>be sure to commit (without pushing) before pulling, if you made changes yourself (otherwise your changes 				    will be gone)</li>
			<li>after you pulled you can push your changes</li>
			<li>if two people change the same file and line there will be some conflicts. be sure to fix them in github or 				    afterwards in unity itself</li>
		</ol>
		<li>Version Control: you can always reset a former stage through the version control in your git-repository</li>
	</ol>
</ol><br>

First Person Exploration Kit Documentation
--------------------------------------------------------------------------------------------------------------------
http://whilefun.com/fpedocs/FPEKitDocumentation.html<br><br>


Tutorial Link for GitHub-Unity-Projects
--------------------------------------------------------------------------------------------------------------------
https://www.youtube.com/watch?v=qpXxcvS-g3g
