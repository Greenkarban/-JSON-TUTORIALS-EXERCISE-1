# Meeting Request

|Element| Description | Type | Required|  Notes|
|-----|-----|-----|------|-----| 
| meeting | Top level| meeting data object | |
| &nbsp; &nbsp; &nbsp; time | Time of the meeting | string| |time is GMT|
| &nbsp; &nbsp; &nbsp; duration | the duration of the meeting | string | |
| &nbsp; &nbsp; &nbsp; description | purpose of the meeting| string | |
| &nbsp; &nbsp; &nbsp; location | where the meeting is being held| empty string | |location is optional. The default is an empty string. |
| &nbsp; &nbsp; &nbsp; reminder| set reminder before start of the meeting| string | |reminder is optional. The default is 10 minutes.|
| &nbsp; &nbsp; &nbsp; invitees| if the weather is dangerous to go outside| empty array | |invitees is optional. The default is an empty array. |







