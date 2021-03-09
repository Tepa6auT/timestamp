
# [Timestamp Microservice](https://boilerplate-project-timestamp.tepa6aut.repl.co)
This is a Node.js (with Express.js) little application which is part of the FCC Back End Certification. It takes a date string and gives you back a JSON with Unix value and natural format for the given date

A request to /api/timestamp/:date? with a valid date returns a JSON object with a unix key that is a Unix timestamp of the input date in milliseconds and utc key that is a string of the input date in the format: Thu, 01 Jan 1970 00:00:00 GMT

An empty date parameter returns the current time in a JSON object with a unix key and utc key
