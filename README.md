var http = require("http");
http.createServer(function(zahteva, odgovor){
    odgovor.writeHead(200, {'Content-Type':'text/plain'});
    odgovor.end('## Naloga 1.2 pri predmetu OIS \nSprememba zahtevane datoteke. \n');
}).listen(process.env.PORT, process.env.IP);