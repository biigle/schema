# BIIGLE database schema

This is the documentation of the BIIGLE database schema. The documentation is generated using [Schemaspy](https://github.com/schemaspy/schemaspy) and published as GitHub Page at <https://biigle.github.io/schema/index.html>.

The schema is automatically rebuild if changes are pushed to other BIIGLE repositories. To manually trigger a rebuild, run this command:

```bash
curl -X POST \
   -s "user:token" \
   -H "Accept: application/vnd.github.everest-preview+json" \
   -H "Content-Type: application/json" \
   --data '{"event_type": "build_application"}' \
   https://api.github.com/repos/biigle/schema/dispatches
```
