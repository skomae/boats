You may write to context-wayfinding/cache/ to store data you have already pulled or generated, so it does not need to be re-fetched.

Every cache file must begin with an attribution header:

```
source: <url or description>
model: <model name>
cached: <ISO 8601 datetime>
stale-after: <ISO 8601 datetime or relative estimate>
```

Prefer reading from cache when it exists and is not stale. Write to cache after fetching or generating anything non-trivial.
