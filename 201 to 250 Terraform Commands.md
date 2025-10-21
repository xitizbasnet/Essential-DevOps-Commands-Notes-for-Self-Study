## 🌍 Terraform Commands

```bash
201. terraform --version                             # Check Terraform version
202. terraform init                                  # Initialize Terraform working directory
203. terraform plan                                  # Show execution plan
204. terraform apply -auto-approve                   # Apply configuration
205. terraform destroy -auto-approve                 # Destroy infrastructure
206. terraform show                                  # Show Terraform state
207. terraform validate                              # Validate Terraform configuration
208. terraform fmt                                   # Format Terraform code
209. terraform providers                             # List providers used
210. terraform state list                            # Show managed resources
211. terraform state show resource_name              # Show specific resource details
212. terraform state rm resource_name                # Remove resource from state
213. terraform taint resource_name                   # Mark resource for recreation
214. terraform untaint resource_name                 # Remove taint from resource
215. terraform import resource_type.name id          # Import existing infrastructure
216. terraform refresh                               # Refresh state file
217. terraform graph                                 # Generate dependency graph
218. terraform workspace list                        # List available workspaces
219. terraform workspace select workspace_name       # Switch workspace
220. terraform workspace new workspace_name          # Create new workspace
221. terraform state mv old_resource new_resource    # Rename resource
222. terraform output                                # Show Terraform outputs
223. terraform output output_name                    # Get specific output value
224. terraform apply -target=resource_name           # Apply specific resource
225. terraform console                               # Open interactive Terraform shell
226. terraform debug                                 # Enable debugging logs
227. terraform version                               # Show installed Terraform version
228. terraform plan -var="instance_type=t2.micro"    # Pass variable via CLI
229. terraform apply -var-file="vars.tfvars"         # Apply using variable file
230. terraform apply -auto-approve                   # Skip manual approval
231. terraform workspace delete workspace_name       # Delete workspace
232. terraform plan -detailed-exitcode               # Get exit codes for changes
233. terraform force-unlock LOCK_ID                  # Unlock Terraform state
234. terraform state push                            # Manually push state file
235. terraform state pull                            # Download current state file
236. terraform output -json                          # Get output in JSON format
237. terraform fmt -recursive                        # Format Terraform in subdirectories
238. terraform destroy -target=resource_name         # Destroy specific resource
239. terraform show -json                            # Show JSON output
240. terraform validate -no-color                    # Validate without colors
241. terraform workspace select default              # Switch to default workspace
242. terraform plan -var 'region=us-east-1'          # Pass a variable inline
243. terraform apply -refresh-only                   # Only refresh state, do not modify
244. terraform state replace-provider old new        # Replace provider
245. terraform plan -out=tfplan                      # Save plan output
246. terraform apply tfplan                          # Apply saved plan
247. terraform version -json                         # Output Terraform version in JSON
248. terraform workspace show                        # Show current workspace
249. terraform plan -var-file=config.tfvars          # Use a variable file
250. terraform output -state=terraform.tfstate       # Show output from a specific state file
```
