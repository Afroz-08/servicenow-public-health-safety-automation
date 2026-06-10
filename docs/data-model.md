# Data Model

## Main Table: Health Service Request

| Field Name | Type | Purpose |
|------------|------|---------|
| Number | Auto Number | Unique request ID |
| Citizen Name | String | Requestor name |
| Symptoms | Choice | Health issue category |
| Severity | Choice | Urgency level |
| Priority | Choice | Auto-assigned priority |
| Appointment Required | True/False | Appointment request |
| Preferred Date | Date | Appointment preference |
| Status | Choice | Lifecycle tracking |
| Assigned To | Reference | Healthcare staff |
| Notes | String | Additional details |
