# Authenticate User
## POST /auth/token
> Generates an access token for API authentication.

# Get User Profile
## GET /users/{userId}
> Retrieve details of a specific field engineer.
> **Use case:** Show path parameters, role attributes, and profile metadata.

# List Assigned Jobs
## GET /jobs
> Returns a list of service jobs, optionally filtered.

**Query params**:
* status (scheduled, in-progress, completed)
* assignedTo
* daterange
**Use case:** Filtering, pagination, query param documentation.

# Create Service Job
## POST /jobs
> Creates a new service job request.
**Request body includes:**
* Customer details
* Asset ID
* Issue description
* Priority

**Use case:** Complex request body schema + validation rules.

# Update Job Status
## PATCH /jobs/{jobId}
> Update job lifecycle state:
* scheduled > in-progress > completed

# Get Asset Details
## GET /assets/{assetId}
> Retrieve equipment details, maintenance history, and status.

**Use case:** Nested objects, arrays, historical data representation.

# Submit Service Report
## POST /jobs/{jobId}/reports
>  Submit a structured service report after job completion.

**request includes:**
* Work performed
* Parts replaced
* Observations
* Attachments (URLs)

**Use case:** Nested JSON, file references, domain-specific terminology.

# Get Notifications
## GET /notifications
> Fetch system notifications for the user.

**Use case:** Event-driven design, timestamps, unread states.