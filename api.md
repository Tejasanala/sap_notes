🔹 ProxyEndpoint
This is the entry point where the client calls your API proxy.

PreFlow (0):

This flow runs before any conditional flows (like checking the request path or verb).

You currently have 0 policies here — meaning nothing runs before the main flow starts.

PostFlow (0):

This runs after the request is sent to the backend but before the response is returned to the client.

Again, 0 policies — so no response transformations or logging happening at this point.

🔹 TargetEndpoint: default
This is the backend system your API proxy is calling (the actual service).

PreFlow (9):

9 policies are running before the request is sent to the backend.

This could include security checks, token validation, transformations, logging, etc.

PostFlow (1):

1 policy runs after getting the response from the backend.

Common examples: response transformation, adding headers, masking sensitive info.



----

So, when you see request.verb = "POST" in code (usually in SAP, Node.js, or other backend frameworks), it means the client is sending data to create a new resource.




Using through API Provider , or each through the url

- Need to change the Host Alias to get that proxy.