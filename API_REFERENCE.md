# API reference

HTTP parsing policy is deterministic and side-effect free except for `httpRequest`. Header validation rejects control characters and the request wrapper bounds method and URL length before crossing the host boundary.

