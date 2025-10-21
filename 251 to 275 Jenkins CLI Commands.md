## 🧪 Jenkins CLI Commands

```bash
251. java -jar jenkins-cli.jar -s http://localhost:8080/ help                      # Show CLI help
252. java -jar jenkins-cli.jar -s http://localhost:8080/ list-jobs                 # List all jobs
253. java -jar jenkins-cli.jar -s http://localhost:8080/ build job_name           # Trigger a job
254. java -jar jenkins-cli.jar -s http://localhost:8080/ console job_name         # View job console output
255. java -jar jenkins-cli.jar -s http://localhost:8080/ delete-job job_name      # Delete a job
256. java -jar jenkins-cli.jar -s http://localhost:8080/ disable-job job_name     # Disable a job
257. java -jar jenkins-cli.jar -s http://localhost:8080/ enable-job job_name      # Enable a job
258. java -jar jenkins-cli.jar -s http://localhost:8080/ safe-restart             # Restart Jenkins safely
259. java -jar jenkins-cli.jar -s http://localhost:8080/ set-build-description job_name 1 "Updated Description"  # Update build description
260. java -jar jenkins-cli.jar -s http://localhost:8080/ version                  # Show Jenkins version
261. java -jar jenkins-cli.jar -s http://localhost:8080/ who-am-i                 # Check authenticated user
262. java -jar jenkins-cli.jar -s http://localhost:8080/ get-job job_name         # Get job config
263. java -jar jenkins-cli.jar -s http://localhost:8080/ set-job job_name < config.xml  # Set job config
264. java -jar jenkins-cli.jar -s http://localhost:8080/ shutdown                 # Shutdown Jenkins
265. java -jar jenkins-cli.jar -s http://localhost:8080/ reload-configuration     # Reload Jenkins configuration
266. java -jar jenkins-cli.jar -s http://localhost:8080/ install-plugin plugin-name  # Install a plugin
267. java -jar jenkins-cli.jar -s http://localhost:8080/ list-plugins             # List installed plugins
268. java -jar jenkins-cli.jar -s http://localhost:8080/ delete-plugin plugin-name  # Delete a plugin
269. java -jar jenkins-cli.jar -s http://localhost:8080/ update-job job_name < config.xml  # Update job configuration
270. java -jar jenkins-cli.jar -s http://localhost:8080/ build job_name -p PARAM=value  # Trigger job with parameters
271. java -jar jenkins-cli.jar -s http://localhost:8080/ safe-exit                # Gracefully stop Jenkins
272. java -jar jenkins-cli.jar -s http://localhost:8080/ disconnect-node node_name  # Disconnect a node
273. java -jar jenkins-cli.jar -s http://localhost:8080/ install-plugin plugin.hpi  # Install plugin from file
274. java -jar jenkins-cli.jar -s http://localhost:8080/ get-view view_name       # Get view configuration
275. java -jar jenkins-cli.jar -s http://localhost:8080/ create-view view_name < config.xml  # Create a new view
```

