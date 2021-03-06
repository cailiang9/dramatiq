.. References

.. |DramatiqError| replace:: :class:`DramatiqError<dramatiq.DramatiqError>`
.. |GenericActors| replace:: :class:`class-based actors<dramatiq.GenericActor>`
.. |MemcachedRLBackend| replace:: :class:`Memcached<dramatiq.rate_limits.backends.MemcachedBackend>`
.. |MiddlewareError| replace:: :class:`MiddlewareError<dramatiq.middleware.MiddlewareError>`
.. |RabbitmqBroker_join| replace:: :meth:`join<dramatiq.brokers.rabbitmq.RabbitmqBroker.join>`
.. |RabbitmqBroker| replace:: :class:`RabbitmqBroker<dramatiq.brokers.rabbitmq.RabbitmqBroker>`
.. |RateLimiters| replace:: :class:`RateLimiters<dramatiq.rate_limits.RateLimiter>`
.. |RedisBroker| replace:: :class:`RedisBroker<dramatiq.brokers.redis.RedisBroker>`
.. |RedisRLBackend| replace:: :class:`Redis<dramatiq.rate_limits.backends.RedisBackend>`
.. |Results| replace:: :class:`Results<dramatiq.results.Results>`
.. |SkipMessage| replace:: :class:`SkipMessage<dramatiq.middleware.SkipMessage>`
.. |StubBroker_flush_all| replace:: :meth:`flush_all<dramatiq.brokers.stub.StubBroker.flush_all>`
.. |StubBroker_flush| replace:: :meth:`flush<dramatiq.brokers.stub.StubBroker.flush>`
.. |StubBroker| replace:: :class:`StubBroker<dramatiq.brokers.stub.StubBroker>`
.. |TimeLimitExceeded| replace:: :class:`TimeLimitExceeded<dramatiq.middleware.TimeLimitExceeded>`
.. |URLRabbitmqBroker| replace:: :class:`URLRabbitmqBroker<dramatiq.brokers.rabbitmq.URLRabbitmqBroker>`
.. |Worker_pause| replace:: :meth:`Worker.pause<dramatiq.Worker.pause>`
.. |Worker_resume| replace:: :meth:`Worker.resume<dramatiq.Worker.resume>`
.. |actor| replace:: :func:`actor<dramatiq.actor>`
.. |add_middleware| replace:: :meth:`add_middleware<dramatiq.Broker.add_middleware>`
.. |after_skip_message| replace:: :meth:`after_skip_message<dramatiq.Middleware.after_skip_message>`
.. |before_consumer_thread_shutdown| replace:: :meth:`before_consumer_thread_shutdown<dramatiq.Middleware.before_consumer_thread_shutdown>`
.. |before_worker_thread_shutdown| replace:: :meth:`before_worker_thread_shutdown<dramatiq.Middleware.before_worker_thread_shutdown>`
.. |dramatiq| replace:: :mod:`dramatiq`
.. |rate_limits| replace:: :mod:`dramatiq.rate_limits`
.. |send_with_options| replace:: :meth:`send_with_options<dramatiq.Actor.send_with_options>`
.. |send| replace:: :meth:`send<dramatiq.Actor.send>`

.. _gevent: http://www.gevent.org/
.. _Memcached: http://memcached.org
.. _RabbitMQ: https://www.rabbitmq.com
.. _Redis: https://redis.io
