# NoSQL-JSON-Fix
Sample of JSON NoSQL Injection Fixing
-----------------------------------------
As we see in the image below we have a vulnerable JSON Code
![Image of mahmoudashraf1344](https://github.com/0x1mahmoud/NoSQL-JSON-Fix/blob/main/Js-Code-Testing.jpg)

This JSON Code is vulnerable with NoSQL Injection
### Description:
As we can this allow the attacker can access into admin panal without knowing the password
We will use a simple thing like **String**...

### Example:
`User.find({ username: req.body.username, password: String(req.body.password }, function (err, users) {`

Check the source code i've putted it.
