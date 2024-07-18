# Meetup 04 March 2024
Meetup at [Liip AG](https://liip.ch), Limmatstrasse 183.

## Firefighting a Symfony & Elasticsearch app with Blackfire

This talk will cover the journey and findings of firefighting a complex Symfony application (build on top
of multiple Symfony components and technologies SF Messenger, SF Serializer, Varnish, Redis,
RabbitMQ, and Elasticsearch) with the help of Blackfire.
The journey covers multiple topics like: Bottlenecks within the SF Serializer, Caching serialized
object, Digging into Elasticsearch APIs and its internals data structures.
The finale will present how the root cause of spikes of http-500 errors in a public facing
API with 2M requests was found.

* Presented by: [Emanuele Panzeri](https://phpc.social/@thepanz)
* Slides: [symfony-elasticsearch-firefighiting-with-blackfire.pdf](./symfony-elasticsearch-firefighiting-with-blackfire.pdf)

##  Symfony Messenger Demo

This presentation will focus on showing a demo application to explain how to use Symfony Messenger
in an application.
David will show the relevant code from the application so you can see how to use Messenger.
Additionally, David has some slides to explain the key concepts of Symfony Messenger and
message queues in general.

* Presented by: [David Buchmann](https://phpc.social/@dbu)
* Slides: https://davidbu.ch/slides/2024-03-04-symfony-messenger.html
* Demo: https://github.com/dbu/messenger-demo/
