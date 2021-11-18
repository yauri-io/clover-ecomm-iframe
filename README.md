# Clover E-Commerce iFrame

This is an example of [Clover E-Commerce iFrame](https://docs.clover.com/docs/using-the-clover-hosted-iframe).
<br />
Merchant's E-Commerce token must be passed in the URL query as `token`.
<br />
By default, the environment is `production`. To change to Clover sandbox environment, pass `environment=sandbox` in 
the URL query.

Example URL:
- ?token={ECOMM_TOKEN} --> For production
- ?token={ECOMM_TOKEN}&environment=sandbox --> for sandbox
---
#### Note
The `environment` only accepts value `sandbox` or `production` (default, no need to set)
