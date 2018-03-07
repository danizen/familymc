# familycmc

## Sumary

Infrastructure as code to setup a minecraft server for my family.

## More Details

Uses ansible and maybe gcloud/aws cloudformation to setup minecraft server.

Hopefully, the map and other aspects can come from elsewhere

## Status

- `Vagrantfile` brings up an environment using vagrant I can connect to from a Minecraft client.  This is more of a test bed than the real thing.

## To Do

- Must add server plugins to the `playbook.yml` using hooks in the minecraft role, e.g. run these after installation but before start.

