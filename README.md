# Work-Work Handbook

![Work-Work Handbook](/www/Work-Work Handbook.jpg?raw=true)


# Serving this as a website:

`docker build -t handbook .`

`docker run --name handbook-nginx -d -p 8080:80 handbook`

Now go to `dockerip:8080`, and have a look at the handbook.


