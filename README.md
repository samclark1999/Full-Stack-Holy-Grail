# Full-Stack-Holygrail
## Description
This is a full stack app that uses React, Node and Redis to update state on the Holy Grail front end template as well as the back end using Redis on top of Docker. Also, Superagent is used to communicate with the server and Express handles API's. The user should be able to update the numbers using icons on each component of the Holy Grail Application on the front end and access that in JSON on the back end with Redis.

## How to Run
Clone Repository and then do an npm install to install necessary dependencies such as Express, and Redis. Then use docker run -p 6379:6379 --name some-redis -d redis to setup the Docker Instance on your local machine. Finally, run node index.js and navigate to localhost:3000. Use routes to access database and home route.

## License

MIT License

Copyright (c) 2020 Sam Clark

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
