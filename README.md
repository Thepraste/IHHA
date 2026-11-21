## Backend integration

1. In `app.js`, set `API_URL` to the agency's HTTPS application endpoint.
2. Confirm the endpoint's expected JSON property names, authentication requirements, response format and error format with the agency's API documentation.
3. Confirm whether the API accepts SSNs in the current format and whether the endpoint requires a different secure transport or encryption scheme.
4. Test successful submissions, validation errors, duplicate submissions, network failures and mobile devices in a staging environment.
