How to run this in your local server?

1) Clone the repository to your PC (or) Computer.
2) Open the coding in Visual studio (or) any other apps.
3) Install all dependencies.
4) Run the server.
5) Open the Postman applicaton.
6) Change the HTTP to POST and set this url http://localhost:3000/api/supplier/query.
7) Set the Header
   Key Content-Type
    and Value application/json.
8) In Body change to Raw and make sure it's in JSON.
   Give the value for Location,Nature_of_business,Manufactruing_processes.
   Example: 
   {
     "location": "India",
     "nature_of_business": "medium_scale",
     "manufacturing_processes": "Printing"
   }
9) The final output will shown in the Postman itself.