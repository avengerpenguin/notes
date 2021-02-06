Notes on FOSDEM talk.

## Web Eras

### 1991 Simplicity

Docker

- Feedback loop: consolidation -> scale -> complexituy -> consolidation

## Web Protocol Issues

- Security has always been an afterthought
- Privacy doesn't even come up -- you need your own web server
- Commercial interests drive innovation more than user interests

HTTP/2 and HTTP/3 are basically Google's SPDT and QUIC respectively. All changes are to do with scale and not for the case where you run your own web server.

- HTTP is and isn't CRUD
- Updates and partial retrieval are broken (range headers aren't used widely, POST/PATCH are not defined; it varies by type/resource intepretation)

"Hard to make a generic web client"

Therefore the server "owns" the data and only it knows how to work with it.

## HTML Issues

HTML 5 gave up on standardisation (living standard).

Google de fact owns HTML5 via WebKit.

HTML mixes data and representation. With JavaScript, it also mixes prrocessing.

This leads to data silos. Data only accessible via linked View/Controller.

## Strengths

HTTP and HTML are simple.

## Whither Web?

### Censorship

Centralised data means censorship is possible.

### Centralisation as Default

Signal creator things third party clients no longer have a place.

### Yielding Control as Default

Less concern for open exchange formats.

## Collaboration

Main need for a human-centric Internet is collaboration

### Mechanics

- Communication
- Sharing stuff (more of barter/trade than social media -- i.e. broadcasting/retweeting) -- Makes me thinkg of 

