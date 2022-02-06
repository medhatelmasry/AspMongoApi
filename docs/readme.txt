docker run -p 27777:27017 --name mgo -d mongo:4.1.6

db.Students.insertMany(
[
  {'FirstName':'Sue','LastName':'Fox','School':'Business'},
  {'FirstName':'Tom','LastName':'Max','School':'Mining'},
  {'FirstName':'Ann','LastName':'Lee','School':'Nursing'},
  {'FirstName':'Joe','LastName':'Roy','School':'Tourism'},
  {'FirstName':'Jan','LastName':'Ash','School':'Communications'},
  {'FirstName':'Eva','LastName':'Day','School':'Medicine'},
]);

dotnet new webapi -f net6.0 -o AspMongoApi

