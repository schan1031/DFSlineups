## Schema

### Users

Column Name | Data Type | Details
---|---|---
id | integer | not null, primary key
username | string | not null
password_digest | string | not null

### Lineups

Column Name | Data Type | Details
-|-|-
Player List | array, string | not null
Date | date or string | not null
user_id | integer | not null
