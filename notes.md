Tackle low hanging fruit first - the happy path. in a perfect world, how should the system work. - the edge cases. Invalid data, network problems.

Writing tests is also a system's design exercise.

EVERYTHING IS A FUNCTION OR A VALUE.

function (optional args) {return a value}

component (optional props) { return UI}

API

- Endpoint (optional data(body/url param/query string/header)) {return JSON data (string) }

## User Story

As a role
I want ...
So that ... the value the user gets

## Scenario

```
GIVEN a valid username
    and and invalid password
    and
WHEN the user clicks login
THEN the user should not be logged in
    and the system responds with status code 401
    and
```
