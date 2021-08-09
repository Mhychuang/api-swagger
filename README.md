# api-swagger
Using swagger to document API
following link shows documentation of this express api 
https://mike-swagger.herokuapp.com/api-docs/

instead of placing swagger comments in app copy.js
I put it in swagger.json 
and import it into app.js
for more ymal comments please check it out here:
https://editor.swagger.io/


## To deploy on herolu
create a heroku account

Run
    
            heroku create [nameofyourURL]

And then push to that app

      git push heroku main

Make sure package.json is step up coreect. 
Make sure port is setup like

     const PORT = process.env.PORT || 3000;
     app.listen(PORT,()=>console.log('Listening on 4000'))


##reference
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/deployment
