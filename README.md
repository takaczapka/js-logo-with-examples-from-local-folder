Start static files [http server](https://www.npmjs.com/package/http-server) - it lets *logo* files which live in *logo/* folder to be served at <http:localhost:8080>. 

Start it with: `./http-server/bin/http-server --cors logo/`.

*jslogo* (https://github.com/inexorabletash/jslogo) is modified to show contents of folders served by *http-server* starting at *http://localhost:8080*. Open jslogo/index.html in browser (ideally Chrome): `open jslogo/index.html`.

`run.sh` script executes both described actions.
