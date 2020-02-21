# json2hp
conver JSON to http parameters file (.default.hp)

### PUT /api/v1/profiles/:id/:action

Save a profile with {id} Or
Update the status of a profile with {id}.

#### Request

##### Parameters

| name | type | mandatory | description |
|------|------|-----------|-------------|
| id   | int64 | Yes | profile ID |
| action | string | Action on profile: `save|submit|send-back|send-for-approval|approve|reject` |
