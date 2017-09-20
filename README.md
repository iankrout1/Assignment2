html>
	<!-- Ian Krout
		 9/21/17
		 Assignment 2 -->
   <head>
      <title>
        Donnelly Hall Adventure
      </title>
	
		<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
			<script type="text/javascript">
			
				function btnNorth() {
					alert("You are at security, they say they saw your dog but can't say where he is for sure since its a circular building..."); 
					document.getElementById("maintext").value = "Now what?"; }
				
					function btnSouth() {
						alert("You leave the building. Try again.");
						document.getElementById("maintext").value="Get back inside and find your dog!";
					}
						function btnEast() {
							alert ("You head down to the chemistry lab and hear barking");
							document.getElementById("maintext").value="You almost got him!";
							}
								function btnWest() {
									alert ("Donnelly! You found your dog, sitting by the fashion lab.");
									document.getElementById("maintext").value="Congrats!";
								}
      </script>
      <style>
         .footer {color: purple; font-weight: bold;}
      </style>
   </head>
   <body>
      <h1>
          The Race to Save Donnelly
      </h1>
		<h2>
			By: Ian Krout
		</h2>
      <textarea rows="5" cols="44" id="maintext" name="maintext"> You enter Donnelly Hall in a panic realizing your dog, Donnelly, has gotten loose and made his way to his favorite building. You must find him!
      </textarea>

      <br />
      
      <input type="button"
             id = "btnNorth"
             name="btnNorth"
             value="North" 
             onclick="btnNorth();" />
			 
		<input type="button"
				id = "btnSouth"
				name="btnSouth"
				value="South" 
				onclick="btnSouth();" />
			 
				<input type="button"
					id = "btnEast"
					name="btnEast"
					value="East" 
					onclick="btnEast();" />
		
					<input type="button"
						id = "btnWest"
						name="btnWest"
						value="West" 
						onclick="btnWest();" />
						
      <p class="footer">
		Questions sent to <a href="mailto:krout.ian@gmail.com"> Ian Krout </a>
      </p>
   </body>
</html>
