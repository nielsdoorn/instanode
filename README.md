# Instagram node demo
Just an example of how to use the Instagram API with a node.js server and query for geo tagged images livestreams and then plot the coords on a open streetmaps map.


## To configure it

It reads three parameters from the environment:

* CALLBACK_URL - for the instagram server to send new events (your host needs to be accessable for instagram)
* CLIENT_ID - your instagram client id (register an application at instagram)
* CLIENT_SECRET - yor instagram client secret


## To run it

demo.js is the server node.js script.

```bash
node demo.js
```