Project contains an app for S60 platform on mobile phones, which will receive SMS from client forward received text to Server running on pc, Server will serve the request and return the suitable String to be returned to the client, app running on phone will return text received from server in response to clients query to client.

Instructions:
<br>1. Install SMS_Service_Agent.sis on phone.<br>
<br>2. Modify public static String fetchDatabaseResult(String received_text) method in Utils.java file to return customized results for query from client in 'received_text'.<br>
<br>3. Start Server by running server java class, it contains main type.<br>
<br>4. note IP address of the server running.<br>
<br>5. Start app on the phone and enter IP address just noted and port as 4444.<br>
<br>6. Everything is ready, let's serve the world via SMS!<br>
<br>
Note: App installed on phone connects to the Server through GPRS connection, phone must have working gprs connection.<br>
<br>
<br>
Developed and Maintained by <a href='http://pratikrokade.com'>Pratik Rokade.</a>