## 🐳 Docker Commands

```bash
101. docker --version                              # Check Docker version
102. docker ps                                     # List running containers
103. docker ps -a                                  # List all containers
104. docker images                                 # List all images
105. docker run -d -p 8080:80 image_name           # Run a container
106. docker exec -it container_id bash             # Access a running container
107. docker stop container_id                      # Stop a container
108. docker rm container_id                        # Remove a container
109. docker rmi image_id                           # Remove an image
110. docker-compose up -d                          # Start containers using Docker Compose
111. docker-compose down                           # Stop and remove all containers
112. docker build -t my_image .                    # Build an image from a Dockerfile
113. docker pull image_name                        # Download an image from Docker Hub
114. docker push myrepo/image_name                 # Push image to registry
115. docker logs container_id                      # View container logs
116. docker inspect container_id                   # Get container details
117. docker network ls                             # List Docker networks
118. docker network inspect network_name           # Inspect network details
119. docker volume ls                              # List Docker volumes
120. docker volume inspect volume_name             # Inspect volume details
121. docker system prune -a                        # Clean up unused containers, images, and networks
122. docker login                                  # Authenticate with Docker Hub
123. docker logout                                 # Logout from Docker Hub
124. docker stats                                  # Show live container resource usage
125. docker top container_id                       # Show running processes inside a container
126. docker tag image_id new_repo:new_tag          # Tag an image
127. docker restart container_id                   # Restart a container
128. docker update --restart=always container_id   # Set restart policy
129. docker rename old_name new_name               # Rename a container
130. docker wait container_id                      # Wait for a container to exit
131. docker events                                 # Show real-time events
132. docker history image_name                     # Show image history
133. docker cp container_id:/path/to/file .        # Copy file from container
134. docker diff container_id                      # Show container file changes
135. docker pause container_id                     # Pause a running container
136. docker unpause container_id                   # Resume a paused container
137. docker info                                   # Show Docker system information
138. docker search image_name                      # Search for an image on Docker Hub
139. docker run --rm image_name                    # Run a container and remove after exit
140. docker network create my_network              # Create a custom Docker network
141. docker network connect my_network container_id  # Connect container to a network
142. docker network disconnect my_network container_id  # Disconnect container from a network
143. docker-compose build                          # Build services defined in docker-compose.yml
144. docker-compose ps                             # List services in a Docker Compose setup
145. docker-compose restart                        # Restart all services in Compose
146. docker-compose logs -f                        # Tail logs for all services
147. docker-compose exec service_name bash         # Run command inside a service container
148. docker-compose scale service=3                # Scale a service to 3 instances
149. docker-compose stop                           # Stop all services without removing containers
150. docker-compose config                         # Validate Docker Compose config
```
