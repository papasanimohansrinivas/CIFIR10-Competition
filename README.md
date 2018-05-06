# papasanimohansrinivas.github.io

<!DOCTYPE html>
<html>
<head>
	<title>Call</title>
</head>
<body>
	<script type="text/javascript">

		var xhr = new XMLHttpRequest();

		var url = "http://174.129.112.60/?properties=%7B%22annotators%22%3A%20%22tokenize%2Cssplit%2Cner%22%2C%20%22date%22%3A%20%222018-04-07T19%3A53%3A11%22%7D&amp;pipelineLanguage=en";

		xhr.open("POST", url, true);

		xhr.setRequestHeader("Content-Type", "application/json");

		xhr.onreadystatechange = function () {
			if (xhr.readyState === 4 && xhr.status === 200) {

				alert(xhr.status);

				var json = JSON.parse(xhr.responseText);
				alert(xhr.responseText);
			}
		};
		// var data = JSON.stringify({"email": "hey@mail.com", "password": "101010"});

		xhr.send("Answering phones, scheduling and confirming appointments, managing cash drawer and processing payments, conduct end-of-day procedures, set & meet deadlines and goals, data entry, interview client, analyze info, meet state credentialing requirements, be honest and law abiding");
		
	</script>

</body>
</html>
