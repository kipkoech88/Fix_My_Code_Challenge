# What was wrong in the codebase

After installing the requirements, I confirmed the error 
<br>
The error is caused by the config of the blueprint 
in the application had url prefix and <br>
also the router in the views had full url which
makes `http://0.0.0.0:500/api/v1/status invalid <br/>
I  fixed the error by fixing the url in the views
