# nb-api
Netbox API Files

This is basically a dumping ground of Netbox API primarily for personal use in Netbox.


With v3.5.0 onward, the [Swagger Editor](https://editor.swagger.io/) complains about requestBody in DELETE actions and won't generate clients.
```
Semantic error at paths./api/circuits/circuit-terminations/.delete.requestBody
DELETE operations cannot have a requestBody.
Jump to line 738
```
Once I can figure out the best way to generate various clients, they will also be included per-version (eg my work requires a csharp client)


Also Note: Please be advised that these API files have additional calls from plugins I have installed on my Netbox host. Overlooked that, so will need to regenerate with a clean host instead.
