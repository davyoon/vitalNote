## Description

Patients often get prescribed the wrong dosage of their medication because doctors only see their readings when they visit the office. VITAL NOTE is a single-page application to help the user's PCP to determine whether their current or new medication is working for them.  Users can keep records of their blood pressure and blood sugar readings. Users can sort readings by month and print out the month's readings.

![Demo](./img/vitalgif.gif)

## Technologies
* HTML/CSS
* JavaScript
* jQuery
* Bootstrap
* Node.js
* Express.js
* Angular.js
* SQLite3
* Browserify
* Watchify
* Passport

## Minimum Viable Product
* Users can log in
* Create, Read, and Delete for blood pressure readings
* Create, Read, and Delete for blood glucose readings
* Insert date/time automatically

## Wireframe
![wireframe](./img/vital_wireframe.jpg)

## ERD
![erd](./img/vital_erd.jpg)

## Routes
Backend

* app.get('/')
* app.get('/login')
* app.post('/login')
* app.get('/logout')
* app.post('/signup')
* app.get('/home')
* app.get('/api/pressures')
* app.post('/api/pressures')
* app.delete('/api/pressures/:id')
* app.get('/api/glucoses')
* app.post('/api/glucoses')
* app.delete('/api/glucoses/:id')

Frontend

* '/pressure'
* '/glucose'
* '/'

## Login
Username - guest
Password - guest

## Deployment
* <a href="https://vital-note.herokuapp.com">Heroku</a>
* <a href="https://github.com/davyoon/vitalNote">Github</a>

