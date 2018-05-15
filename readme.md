# CFPLand Collector
Gets conference data, saves it to JSONBin. Also provides a webtask that converts those JSON files to RSS.

## Running/Deploying the Collector
- Build: `docker build -t karllhughes/cfpland-collector .`
- Run: `docker run -e JSONBIN_STARTS_SOON_ID=... -e JSONBIN_CFP_ENDS_SOON_ID=... karllhughes/cfpland-collector:latest`

## Running/Deploying the Webtask
