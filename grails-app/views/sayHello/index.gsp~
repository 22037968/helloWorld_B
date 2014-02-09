<!DOCTYPE html>
<html>
	<head>
		<meta name="layout" content="main"/>
		<title>Welcome to Grails</title>
	</head>

	<body>
		<h1>This is the sayHello view</h1>
		<form method="post">
			Please enter your name : <input type="text" name="name" value="${params.name}"/>
			<input type="submit"/>
		</form>

		<g:if test="${params.name != null}">
			Hello ${params.name}
		</g:if>
		<g:else>
			Please enter you name
		</g:else>
	</body>
</html>
