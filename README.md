#### Image Hosting for Intel at KubeCon EU 2020

## Changing Status Indicators for Staff

Find the file `status.json` in this repository and edit it within GitHub.

For each staff member's name, the `true` or `false` value will set their booth's avatar to "Available" or "Away", respectively.

Feel free to edit the file within GitHub and commit the changes directly to the `master` branch.

## Default Values

The default values (with everyone as "Away") is the following:

```json
{
  "aibhne": false,
  "ailin": false,
  "beth": false,
  "bobby": false,
  "chris": false,
  "emma": false,
  "eric": false,
  "geoffroy": false,
  "kien": false,
  "killian": false,
  "linjia": false,
  "mike": false,
  "wei": false
}
```

__Note__: That the final line (`"wei": false"`) does not have a trailing comma, while all other lines do have a trailing comma.
Improper JSON formatting will prevent the booth from updating.
