# Sign-off Formats

## Ticket comment

Post a single comment on the open sign-off ticket. It must contain exactly one
block delimited by the two marker comments below, with one line per signed
package in the form `<package>: <license>`:

```
<!-- license-signoff:start -->
<package>: <license>
<package>: <license>
<!-- license-signoff:end -->
```

## Machine-readable record

Create `signoff/q4-license-decisions.json` on the default branch:

```json
{
  "launch": "2026-Q4",
  "decisions": [
    {"package": "<name>", "cycle": "<cycle>", "license": "<license>", "basis": "<source repo id>", "status": "RELEASED"}
  ]
}
```

## Close-out

Close the sign-off ticket once the comment and the file are in place.
