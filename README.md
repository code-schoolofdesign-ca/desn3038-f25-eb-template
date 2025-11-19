# desn3038-f25-eb

## Database credentials

- Hostname: `gbc.goodcodeclub.com`
- Username: `f25_{STUDENTID}`, where `{STUDENTID}` is your student ID (ex. `f25_101010101`)
- Password: `f25_{STUDENTID}`
- Database: `f25_{STUDENTID}_e4` (note `_e4` at the end)

## Checklist / before you begin

- Set up the database
- Install `nodemon` to auto-reload API script (`npm i nodemon -g`)
- Set the visibility of port 3001 to `public`
- Download and extract contents of `/dist` from Swagger UI into `/docs`
- Use GitHub Pages to set the source folder as `/docs`

## Bring up

Wait for the initial Codespaces process to complete.

```
npm i nodemon -g
nodemon backend/main.js
```

Thereafter, click on "Make Public" or use the "Ports" tab.

Have fun!