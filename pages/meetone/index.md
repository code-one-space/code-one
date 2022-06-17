<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Join Meet:One</title>
    <script>
        const query = window.location.search
        const params = new URLSearchParams(query)
        const meetingid = params.get("meetingId")

        if(meetingid) {
            window.location = "exp://192.168.178.22:19000/--/joinscreen?meetingId=" + meetingid
        }
    </script>
</head>
<body>
    
</body>
</html>