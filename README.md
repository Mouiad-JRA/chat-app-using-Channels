# Simple-chat-app-using-Channels

Channels wraps Django’s native asynchronous view support, allowing Django projects to handle not only HTTP, but protocols that require long-running connections too - WebSockets, MQTT, chatbots, amateur radio, and more.

It does this while preserving Django’s synchronous and easy-to-use nature, allowing you to choose how you write your code - synchronous in a style like Django views, fully asynchronous, or a mixture of both. On top of this, it provides integrations with Django’s auth system, session system, and more, making it easier than ever to extend your HTTP-only project to other protocols.

Channels also bundles this event-driven architecture with channel layers, a system that allows you to easily communicate between processes, and separate your project into different processes.

If you haven’t yet installed Channels, you may want to read Installation first to get it installed. This introduction isn’t a direct tutorial, but you should be able to use it to follow along and make changes to an existing Django project if you like.

# <a href="https://channels.readthedocs.io/en/stable/tutorial/index.html"> Tutorial </a>

Channels allows you to use WebSockets and other non-HTTP protocols in your Django site. For example you might want to use WebSockets to allow a page on your site to immediately receive updates from your Django server without using HTTP long-polling or other expensive techniques.

In this tutorial we will build a simple chat server, where you can join an online room, post messages to the room, and have others in the same room see those messages immediately.
