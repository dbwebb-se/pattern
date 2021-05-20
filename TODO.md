# pattern
Course repo for the design pattern and framework course - pattern.

design patterns used in frameworks
    * signleton
    * factory

* anax/configure, how to make o model configurable using interface and trait.
    * Good example on reuse with interface and trait. (kmom02)
    * Change to read configuration in di callback. (kmom03)
    * kmom04 how to separate configuration in test/ versus live app.

(itsec, secure programming)
    * authentication, register account, login, cookie
    * Inloggning med oauth och extern login.
    * Security CSRF, SQL injection, XSS

di, dependency injection (phpfig) (kmom03)

caching (phpfig) (kmom02/03)
    * cache requests from external servers
localization?

unit testing (kmom03)
    * mock external services
    * Start up separate test server, also on travis/scrutinizer

stress testing? (kmom06?)
    * tournament in how fast it can be

code quality (early, build travis on kmom01, scrutinizer on kmom02)

reflection

Code static analysing
Code metrics
    * Analysera någon kod och reflektera, kör flera verktyg. Använd anax som referens och jämför med andra ramverk.

https://phpmetrics.org/

Dokumentation

* phpdox
* phpdoc
* https://github.com/MontealegreLuis/phuml
* https://dbwebb.se/uppgift/dokumentera-php-med-phpdoc-och-phpdocumentor

<!--
https://www.slideshare.net/liopic/code-metrics-in-php
-->

Linters för
    * Säkerhet

https://plantuml.com/ för diagram

Bygga egna designpatterns, som övningar mot existerande testcase

    * Singleton
    * https://martinfowler.com/eaaCatalog/
    * Factory pattern

Rapporten skall slås ihop till ett dokument, som pdf och lämnas in när kursen är slut. Inklusive abstract, summary och referenser. Som träning inför exjobbet. Alternativt är rapporten så att man kan kopiera/paste från redovisnignstexter in i rapporten.

    * Kodkvalitet
    * Kodfilosofi
    * Skriva om designmönster
    * Analysera någon programvara kodmässigt

Build own docker image.
Websockets, real-time web, web hooks, docker and production of a site.
Extern lagrings/cachningsservice (flera i docker-imagen)

Egen bankid tjänst med signering (ger tillfälle till en mer komplett lösning?)

Installera på egen server, kan krävas för oauth.
Inkludera websockets?


Hypertext Application Language, or HAL) is a proposed IETF specification for representing API resources and their relations with hyperlinks. While the original specification targets JSON, an additional IETF proposal targets XML.
http://stateless.co/hal_specification.html

ORM Doctrine with MongoDB?

Use docker and use a virtual host?

TDD, fokus på testbar kod och kodkvalitet och även lokal php-server för att testa mot.

## kmom01 controller

Kunskapsinventering, skapa issue på GitHub med läromål för kursen.

## kmom02 mvc

travis badge

## kmom04 modul

packagist badge

## kmom06 databasmodeller

Övning och träning med databasmodulerna, innan man börjar använda dem.

Enhetstestning mot databas.

Börja med detta tidigare i kursen, så man hinner jobba lite mer. Dels jobba mot query object och dels mot active record.

Visa extern modul och låta dem använda det (ja)?

## kmom10

Diskussionsforum, stackoverflow, reddit.

Tillåter ORM.
