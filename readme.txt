Search engine for employees to search courses (MOOCs) based on some parameters: learning objectives of the employees, objectives of the employer, dependencies between courses, courses followed in parallel, etc.


How-to moocrank

Install stuff!
- install node: apt-get install nodejs
- install mongodb: apt-get install mongodb
- in the root directory, update dependencies: npm install

Configure it!
- install coursera courses: node parser/coursera-parser.js
- install udacity courses: node parser/udacity-parser.js
- install edx courses: node parser/edx-parser.js
- install outcomes database: node parser/outcomes-parser.js

Run it!
- node app.js
- access the app in localhost:3000


** Trobleshooting

Ubuntu users. Commands to Install node 0.10 instead of 0.6:

sudo apt-get install python-software-properties
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs

Debian users. Install using experimental: http://ypcs.fi/howto/2013/03/23/nodejs-debian/