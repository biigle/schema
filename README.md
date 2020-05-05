# BIIGLE database schema

![Build](https://github.com/biigle/schema/workflows/Build/badge.svg)

This is the documentation of the BIIGLE database schema. The documentation is generated using [Schemaspy](https://github.com/schemaspy/schemaspy) and published as GitHub Page at <https://biigle.github.io/schema/index.html>.

The schema documentation is automatically rebuilt if changes are pushed to the BIIGLE core or module repositories. To manually trigger a rebuild, run this command:

```bash
curl -X POST \
   -s "user:token" \
   -H "Content-Type: application/json" \
   --data '{"event_type": "build_application"}' \
   https://api.github.com/repos/biigle/schema/dispatches
```
