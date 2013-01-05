# corsy

Node.js-based [CORS](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing) proxy with HTTP/HTTPS support.
Available live at [corsy.rs.af.cm](http://corsy.rs.af.cm).

## Usage

    curl -v http://corsy.rs.af.cm/?get=https://raw.github.com/shyiko/lorem/master/readme.md
    # corsy will fetch the resourse, add 
    # "Access-Control-Allow-Origin: *; Access-Control-Allow-Headers: X-Requested-With" 
    # to the header and stream response back to the client

## License
Copyright (c) 2012 Stanley Shyiko
Licensed under the MIT license.
    
