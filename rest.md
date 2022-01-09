## REST(Representational State Transfer)
```
The Representational State Transfer (REST) architectural style is a worldview that elevates information into a first-class element of architectures. REST allows us to achieve the architectural properties of performance, scalability, generality, simplicity, modifiability, and extensibility.
```
- `REST` defines 6 architectural constraints which make any web service – a truly RESTful API:
  - `Uniform interface` - Once a developer becomes familiar with one of your APIs, he should be able to follow a similar approach for other APIs.
  - `Client–server` - Servers and clients may also be replaced and developed independently, as long as the interface between them is not altered.
  - `Stateless` - No client context shall be stored on the server between requests. The client is responsible for managing the state of the application.
  - `Cacheable` - Well-managed caching partially or completely eliminates some client-server interactions, further improving scalability and performance.
  - `Layered system` - REST allows you to use a layered system architecture where you deploy the APIs on server A, and store data on server B and authenticate requests in Server C, for example. A client cannot ordinarily tell whether it is connected directly to the end server or an intermediary along the way.
  - `Code on demand` (optional) - Well, this constraint is optional. Most of the time, you will be sending the static representations of resources in the form of XML or JSON. But when you need to, you are free to return executable code to support a part of your application, e.g., clients may call your API to get a UI widget rendering code. It is permitted.
  - All the above constraints help you build a truly RESTful API, and you should follow them. Still, at times, you may find yourself violating one or two constraints. Do not worry; you are still making a RESTful API – but not “truly RESTful.”
---

## REST Shortcomings
- gets all the data when you don't need it and also is hard to handle making queries for highly similar data.
- can over serve data.
- deciding on URL schema gets tough when we have heavily nested relationships.
- when fetching heavily nested data we can have an issue where we make too many HTTP requests.
---