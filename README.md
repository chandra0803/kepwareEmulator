# Opto Connect Host Adapter
This adapter connects a customer host WMS system to a WES system.  It provides validation of incoming messages from 
the host and translation to the standard V1 Host Adapter Interface.

This repository contains only the adapter that connects to the host WMS using coordinating REST APIs.  It connects to 
only Opto WES using RabbitMQ topics.

The adapter expect a facade that is used to customize the host message interface for a particular site.