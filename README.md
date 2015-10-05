#https-angular-flask

This repo contains boiler plate code for a webapp using angularjs which **supports https connections over livereload**

Also a simple flask rest api is provided to test this frontend angular app. Flask api also supports https.

Note: _For testing purpose self signed key were used_

## How to use

** Replace server.key and server.crt with your actual keys. Follow this link to generate your own pair of key and crt file.**
Place newly generated key and crt file in angular-frontend and also in flask-backend folder.

###Running Back end
  1.clone this repo.
  2. `cd flask-backend && python app.py`  **// Imp. Minimum Python version required is 3.0    


###Running Front-end
  1. Go to root of this repo
  2. `cd angular-frontend && npm install`
  3. `bower install`
  4. `grunt serve`


## Requirements:
  1. Nodejs >0.12
  2. npm >2.14
  3. python >3.0

**For install instructions about nodejs and npm checkout this repo [why-I-lost-hair](https://github.com/deathping1994/why-I-lost-hair)**
## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.
