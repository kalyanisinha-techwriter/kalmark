## Success — 201 Created 

{
  "jobId": "JOB-56789",
  "status": "scheduled",
  "createdAt": "2026-05-14T20:12:45Z",
  "priority": "high",
  "assignedTo": "USR-10293",
  "links": {
    "self": "/v1/jobs/JOB-56789",
    "report": "/v1/jobs/JOB-56789/reports"
  }
}

## Error Responses

* 400 Bad Request
> Invalid or missing required fields.

{
  "error": {
    "code": "INVALID_REQUEST",
    "message": "Missing required field: assetId"
  }
}

* 401 Unauthorized
> Missing or invalid authentication token.

{
  "error": {
    "code": "UNAUTHORIZED",
    "message": "Access token is missing or invalid"
  }
}

*  404 Not Found
>  Referenced resource (e.g., assetId) does not exist.