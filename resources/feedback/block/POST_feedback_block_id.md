# Feedback Block Resources
    POST feedback/:feedback_id/block/:id

## Description
Update a feedback block

## Requires authentication
- Details described [here](/README.md#authentication)

## Parameters
- `status`_(optional)_ - change feedback block status ([reference](/reference/feedback/block/status.md))

## Example
**Request**

    POST https://api.platform.onesky.io/1/project/:project_id/feedback/:feedback_id/block/:id

**Response**
```
status 200 OK
```