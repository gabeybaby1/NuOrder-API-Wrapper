# NuOrder-API-Wrapper
simple python wrapper class for nuOrder's API

just call the class and initialize it with "POST" or "GET", then the target NuOrder URL, and the info packet:
Example: newCall = APIWrap("GET", "https://next.nuorder.com/api/orders/approved/detail?", None)

to execute it, call the "APICall()" function:
Example: newCall.APICall()

this will return the whole response.
