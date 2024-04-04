Detailed documentation on: https://docs.google.com/document/d/1P-vlZlgo829U_-NhPK2uD5bSmyDWn4M-sdoUkpR3z34/edit


## Usage:
```
# Install dependencies
npm install

# Start server
node server.js
```
## API details
- GET /
    - returns "Hello World"
- GET /load
    - query params:
        - scale -> time(ms) for which CPU will be blocked (default=random between 0ms to 10ms)
    - returns "OK" after execution

## Notes:
- App runs on port 8081
- Tested with node v14 and npm v7
