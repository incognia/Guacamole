# Guacamole

## What is Guacamole?
Guacamole is an HTML5 web application that provides access to desktop environments using remote desktop protocols (such as VNC or RDP). Guacamole is also the project that produces this web application, and provides an API that drives it. This API can be used to power other similar applications or services.

“Guacamole” is most commonly used to refer to the web application produced by the Guacamole project using their API. This web application is part of a stack that provides a protocol-agnostic remote desktop gateway. Written in JavaScript and using only HTML5 and other standards, the client part of Guacamole requires nothing more than a modern web browser or web-enabled device when accessing any of the desktops served.

Historically, Guacamole was an HTML5 VNC client, and before that, a JavaScript Telnet client called RealMint (“RealMint” is an anagram for “terminal”), but this is no longer the case. Guacamole’s architecture has grown to encompass remote desktop in general, and can be used as a gateway for any number of computers. Originally a proof-of-concept, Guacamole is now performant enough for daily use, and all Guacamole development is done over Guacamole.

As an API, Guacamole provides a common and efficient means of streaming text data over a JavaScript-based tunnel using either HTTP or WebSocket, and a client implementation which supports the Guacamole protocol and renders the remote display when combined with a Guacamole protocol stream from the tunnel.

It provides cross-browser mouse and keyboard events, an XML-driven on-screen keyboard, and synchronized nestable layers with hardware-accelerated compositing. Projects that wish to provide remote desktop support over HTML5 can leverage the years of research and development that went into Guacamole by incorporating the API into their application

## Why use Guacamole?

The principle reason to use Guacamole is constant, world-wide, unfettered access to your computers.

Guacamole allows access one or more desktops from anywhere remotely, without having to install a client, particularly when installing a client is not possible. By setting up a Guacamole server, you can provide access to any other computer on the network from virtually any other computer on the internet, anywhere in the world. Even mobile phones or tablets can be used, without having to install anything.

As a true web application whose communication is over HTTP or HTTPS only, Guacamole allows you to access your machines from anywhere without violating the policy of your workplace, and without requiring the installation of special clients. The presence of a proxy or corporate firewall does not prevent Guacamole use.