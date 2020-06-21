# web-serial-terminal
Fully web based serial terminal using Serial Web API - Access your serial / USB-Serial device directly from the browser!

Working example: https://ain.ufscar.br/aroca/web-serial-terminal/

Works on vanilla Google Chrome with Experimental Web Platform Features enabled in chrome://flags (#enable-experimental-web-platform-features)

When using on a webserver, due to security restrinctions Web Serial API will only worked if served from an HTTPS server. If deployed to HTTP, the connect button will be disabled.
