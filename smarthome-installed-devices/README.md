## Configs for the currently installed Smarthome esp devices

Stored here to keep them separate from the experiments. 
This is mainly so that they can be easily updated on a more powerful machine.

## Updating
To update esphome itself, run `brew install esphome` 
   
To update a particular device, run `esphome run device-name.yaml`

## Troubleshooting
### OTA Fails due to size
If OTA fails due to binary size, comment out encryption, build, deploy. Then uncomment and rebuild and deploy.