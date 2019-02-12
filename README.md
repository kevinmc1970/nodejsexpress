# nodejsexpress
simple nodejs express code for learning

includes a /index.htm mapping which returns back the index.htm file (i.e. http://localhost:8081/index.htm)
- this shows that nodejs can be used as a complete e2e website (ala servlets)
- the page has a simple form which submits to /process_get and express reads the values and logs to console (i.e. req.query.first_name)
-- it also stringifies the json and returns it in the response (res.end(JSON.stringify(response))

N.B. *** the package.json file went missing but re-creaed using interactive npm init ***
N.B. *** I created the git repo AFTER the code so node_modules was included - created .gitignore to remove ***





