First, retrieve the stack YML manifest:

```
curl -L https://raw.githubusercontent.com/PhilipMello/portainer/refs/heads/main/portainer-agent-stack.yml -o portainer-agent-stack.yml
```

Then use the downloaded YML manifest to deploy your stack:

```
docker stack deploy -c portainer-agent-stack.yml portainer
```
