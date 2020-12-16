# teamcity-docker
Setup a teamcity server and agent in a few commands and clicks

### start environment
- `docker-compose up`
- go to localhost:8111
- follow setup instructions
- authorise agent to server via web ui
- done! begin adding projects and build configurations...

### inspect an agent
`docker exec -it temp_agent_1 bash`

### tear down environment
`docker-compose down`
