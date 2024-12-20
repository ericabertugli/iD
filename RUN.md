# RUN

Run the following commands to start the server with a local schema:

```bash
npm clean-install
npm run all
npm start
```

Then open http://127.0.0.1:8080 in a web browser

## To use a local id-tagging-schema
Add the environment variable ID_PRESETS_CDN_URL to the file `.env`.
E.g.
```bash
ID_PRESETS_CDN_URL=http://localhost:3000/
```