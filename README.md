<html>
 	<head>
 		<title> Phill </title>
		<script>
			function answer(){ 
				var radio = document.getElementsByName("trivia"); 
				var selection = false; 
				var message = "";
				for( var i = 0; i < radio.length; i++) {
					if(radio[i].value == "true" && radio[i].checked == true) { 
							selection = true;
					} //end if statement 
				} //end for loop
				if(selection == true) {
					message = message + "<b><p style='color:green'>Yay! You know the truth!</p></b>"; 
				} else { 
					message = message + "<b><p style='color:red'>You need to realize the truth of this world.</p></b>"; 
				}
					document.getElementById("response").innerHTML = message;
					
			} //end function answer
		</script>
	</head>
	<body id="background">
	<center> <header> MagikarpUsedFly </header> </center>
		<center><nav>
			<ul id="navmenu">
				<li class="navitem"><a href="http://na.leagueoflegends.com/"> League Of Legends.</a></li>
				<li class="navitem"><a href="http://fatefulday.eu/"> When and here you will die.</a></li>
				<li class="navitem"><a href="file:///C:/Users/sa-coding/Desktop/Carter/about%20me.html"> About me.</a></li>
			</ul>
		</nav></center>
		<center><p> The larger the space <u>between your eyes and your noes</u> the more you want to <b>kill your self.</b> :    ^)</p></center>
	<script type="text/javascript"></script>
		<center><ol>
			<li class="listitem"> You have no friends. </li>
			<li class="listitem"> :     ^) </li>
			<li class="listitem"> Nobody loves you. </li></center>
		<center><img id="image"
			src="https://i.ytimg.com/vi/-FYbqqFyuSg/hqdefault.jpg"/></center>
		<center><p>The man with the horn hates his life.</p></center>
		<center><img id="image"
			src="data:image/jpeg;base64,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"/></center>
		<center><div class="wrap-trivia">
			<h2> Death Trivia Question:</h2>
			<p> After Life?? </p>
			<form>
				<div id="response"></div>
				<input type="radio" name="trivia" value="false"> there is a after life. <br> 
				<input type="radio" name="trivia" value="true"> There is no after life. They have been lieing to you your whole life.  <br> 
				<input type="radio" name="trivia" value="false"> There is heaven and a hell. <br> 
				<input type="button" id="submit" value="Click Here" onclick="answer()">
			</form>
			<center>
				<iframe width="560" height="315" src="https://www.youtube.com/embed/l6l-qHW5q8A" frameborder="0" allowfullscreen></iframe>
		</div></center>
		<center> <p> You Will Die! </p> </center>
		<center> <p>Carter :          ^) </p>
		<link type="text/css" rel="stylesheet" href="main.css" />
		<footer> GOO BYE! </footer></center>
	</body>
</html>
