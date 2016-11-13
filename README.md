Start static files http server (https://www.npmjs.com/package/http-server) - it lets to serve static *logo* files from logo/ folder. 

Start it with:
> ./http-server/bin/http-server --cors logo

*jslogo* (https://github.com/inexorabletash/jslogo) is modified to show contents of folders served by *http-server* starting at *http://localhost:8080*. Open jslogo/index.html in browser (ideally Chrome).