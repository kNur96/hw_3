# hw_3
This contains the third homework.<br> 
The link to the deployed web app: <br>
https://limitless-wave-20914.herokuapp.com<br>
User Scenarios: <br>
Gets (retrieves) and processes information about the laureates, this information will not update.<br>
•	GET: /                   <br>
Gets (retrieves) the information on countries. (retries if it fails)<br>
•	GET: /countries                <br>
Gets the information on a country code (i.e. what countries are associated with it)<br>
•	GET: /countries/:id              <br>
Get a list of the first names of the laureates      <br>
•	GET: /laureates               <br>
Gets (calculates) the female to male ratio among the laureates   <br>
•	GET: /laureate/genderData        <br>
Gets (locates) the data\laureate associated with the parameter id        <br>
•	GET: /laureate/:id            <br>
Gets (calculates) the average lifespan of a Nobel laureate       <br>
•	GET: /laureate/Age-info/av_age      <br>
Gets (calculates) the age of a Nobel Laureate (or retrieves their age when they died)      <br>
•	GET: /laureate/find_age/:name          <br>
Posts (adds) a new laureate based on Query String input        <br>
•	POST: /laureates/adds          <br>
Puts (modifies or updates) the name of a user using Query String input   <br>
•	PUT: /laureates     <br>
Deletes a laureate based on the Query String <br>
•	DELETE: /laureates  <br>
 
