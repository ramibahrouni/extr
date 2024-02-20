# 1. High-level design
At a high-level, we need some following services (or components) to handle the functional requirements:

![challenge-architecture](https://hackmd.io/_uploads/BJiQUDbhp.png)


**Ingredients Service**: Get list of Available ingredients, manage to update ingredients quantity.

**User Service**: manage all users service and create new users.

**Order Service**: manages raw orders before send quantity review and cost calculation.

**Order watcher Service**: manages raw orders before send quantity review and cost calculation.

**service-discovery**: manages raw orders before send quantity review and cost calculation.

**config-server**: manages raw orders before send quantity review and cost calculation.

**API Gateway**: Route requests to multiple services using a single endpoint.
This service allows us to expose multiple services on a single endpoint and route to the appropriate service based on the request.
