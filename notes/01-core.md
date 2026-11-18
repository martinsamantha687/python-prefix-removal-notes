# Remove exactly one prefix: implementation

## What the example does

removeprefix matches an entire prefix once. Unlike lstrip, it does not treat the argument as a set of removable characters.

The public function is `solve(value)`. The JSON input contract can be seen in this concrete example:

```json
{
  "text": "log:message",
  "prefix": "log:"
}
```

Expected result:

```json
"message"
```

Run `python3 example.py` for the Python representation of the result. `solution.py` contains the full implementation and can also be imported by another script.

## Scope

The function implements exactly the behavior described above. It does not perform network or filesystem access. Python exceptions indicate unsupported input; the next lesson turns them into a command-line error response. Review the limitations before reusing it in an application.
