# EscapeRoom
MTD2018: Usability and Interaction Design (mtd282)
<br><br><br>

To Clone Repository
--------------------------------------------------------------------------------------------------------------------
<ol>
	<li> Download GitHub Desktop on https://desktop.github.com/ and install</li><br>
	<li>Go under File
		<ol>
			<li>choose Options: and Login with your GitHub Account there</li>
			<li>choose Git: and enter your Name and Email adress</li>
			<li>Save changes</li>
		</ol>
	</li><br>
	<li>Choose Clone a repository from Internet
		<ol>
			<li>first choose your path to your local clone directory</li>
			<li>then if the Repository is listed on the right side you can just choose that one</li>
			<li>otherwise go to repository "EscapeRoom", click the button Clone or Download and copy the link listed 				    there<br>
			    https://github.com/Isa-git/EscapeRoom.git</li>
		</ol>
	</li>
</ol><br>

    
 To Work with Unity
--------------------------------------------------------------------------------------------------------------------   
<ol>
	<li>Open Project and edit Project Settings
	<ol>
		<li>Edit - Project Settings</li>
		<li>Under Editor Tab:
			<ol>
				<li>Version Control - Mode: Visible Meta Files</li>
				<li>Asset Serialization - Mode: Force Text</li>
			</ol>
		</li>
	</ol><br>
	<li>edit Gitignore so it doesn't show and push meta files
		<ol>
			<li>open .gitignore File</li>
			<li>delete / before the project fiels in the beginning - it should now be like:
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
			</li>
			<li>now the unnessessary meta files won't be pushed</li>
		</ol>
	</li><br>
	<li>from now on you can commit the project normally
		<ol>
			<li>choose commit changes</li>
			<li>go to history and right beside the new commmit that is shown, press icon to upload to the git repository<br>
			    or choose Push origin after the branch on top<br></li>
			<li>to pull from repository 
				<ol>
					<li>be sure to commit (without pushing) before pulling, if you made changes yourself (otherwise 					    your changes  will be gone)</li>
					<li>after you pulled (first fetch then pull) you can push your changes</li>
					<li>if two people change the same file and line there will be some conflicts. be sure to fix 						    them in github or afterwards in unity itself</li>
				</ol>
			</li>
			<li>Version Control: you can always reset a former stage through the version control in your git-repository</li>
		</ol>
	</li>
</ol><br>


Hints and Usable Parts (Items)
--------------------------------------------------------------------------------------------------------------------
<ol>
	<li>Schl�ssel zur Schatzkiste: Pick K�nig Hint auf Schachbrett --> Schl�ssel im Kochtopf --> aber Achtung im Kleinen ist ein falscher Schl�ssel, der nichts sperrt (wei�er K�nig) im gro�en der richtige Schl�ssel der sperrt (schwarzer Schl�ssel) --> den Tipp Zettel kann man sonst noch irgendwo anders verstecken --> oder das Aufnahmeger�t am Esstisch oder der Radio obern Bett in der Kommode spielt den tipp Soundm��ig ab - dann is es ned so straight vorward (aufgenommen is es schon)</li>
	<li>WC: Schatzkiste --> Schalter f�r das Bild Oberhalb vom Desk mit dem verschlossenen Schl�ssel</li>
	<li>hinter Bild: Kombinationsschloss f�r T�re zum Blood Room +  Schl�ssel zum Schreibtischfach</li>
	<li>Im Schribtischfach: 4 Fotos --> Alle beziehen sich auf einen Rohstoff und darunter steht eine Bewertung des Fotografen wie es ihm gefallen hat --> Muss nun so gereiht werden, von bestes Erlebnis zu schlechtestem --> Wiese, Gold, �dland, Erz,  - 4, 7, 2, 3</li>
	<li>Kombination f�r Kombinationsschloss hinter Bild --> T�re zum Blood Room geht auf (vorerstes Ende --> geht aber auch schon davor)</li>
	<li>F�r die n�chste Kombination (letzte), muss man 4 W�rfel finden --> 2 sind beim Spielbrett schon dabei, die anderen zwei wei� ich noch nicht wo wir die verstecken. L�sung sind immer die Zahlen die oben stehen (man kann sie also nicht aufheben). wir brauchen also noch 3 hints --> w�rde das mit den b�chern machen (wei� aber noch nicht wie).</li>
	<li>Die Kombination sperrt einerseits die Fake T�re auf aber w�rde auch dei Wand im Blood Room aufschwingen lassen (das wei� man aber nicht).</li>
	<li>Spieler wird versuchen die Hauptt�re aufzusperren geht auf und Wand ist dahinter</li>
	<li>Er sucht weiter, findet eine verschlssene Truhe, in der befindet sich noch mal ein Zahlenschloss (w�rde ich evtl. in den Blood Room geben oder Kasten???</li>
	<li>Schl�ssel ist hinter des Blood Room Tisches (einziger Hint ist das umgedrehte Buch.</li>
	<li>Wenn der Schl�ssel gefunden ist, wird die Truhe oder Box aufgesperrt, es kann der Code eingegeben werden und voila drau�en sind wir</li>
</ol>

Ich hab die Reihenfolge etwas umgestellt - falls es ned passt k�nn mas gern wieder umdrehen. Dar�ber hinaus sind auch relativ viele m�gliche R�tsel drinnen, bei denen man Gegenst�nde z�hlen muss. Weil wir so viele ssachen drinnen haben. Glaubst du ist das noch zu komplex?
<br>
Ich hab auch die neuen Polaroid noch gemacht - 4 im Schreibtisch und 1 im Tisch im Blood Raum. Das n�chste was ma dann machen m�ssen sind die ersten 2 Schritte Programmieren.

<br><br><br>


First Person Exploration Kit Documentation
--------------------------------------------------------------------------------------------------------------------
http://whilefun.com/fpedocs/FPEKitDocumentation.html<br><br><br>


Tutorial Link for GitHub-Unity-Projects
--------------------------------------------------------------------------------------------------------------------
https://www.youtube.com/watch?v=qpXxcvS-g3g
