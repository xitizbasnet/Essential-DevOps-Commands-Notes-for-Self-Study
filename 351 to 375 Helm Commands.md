## 🎯 Helm Commands

```bash
351. helm version                                      # Check Helm version
352. helm repo add stable https://charts.helm.sh/stable  # Add Helm repository
353. helm repo update                                  # Update Helm repositories
354. helm search repo nginx                            # Search for a Helm chart
355. helm install myapp stable/nginx                   # Install a Helm chart
356. helm upgrade myapp stable/nginx                   # Upgrade a Helm release
357. helm rollback myapp 1                             # Rollback release to a previous version
358. helm uninstall myapp                              # Uninstall a Helm release
359. helm list                                         # List all installed Helm releases
360. helm status myapp                                 # Show the status of a Helm release
361. helm get values myapp                             # Show values used in a Helm release
362. helm get manifest myapp                           # Show Kubernetes manifests of a release
363. helm template myapp stable/nginx                  # Render chart templates locally
364. helm lint mychart/                                # Validate Helm chart syntax
365. helm package mychart/                             # Package a Helm chart
366. helm repo remove stable                           # Remove a Helm repository
367. helm dependency update mychart/                   # Update chart dependencies
368. helm dependency build mychart/                    # Build chart dependencies
369. helm history myapp                                # Show the history of a Helm release
370. helm create mychart                               # Create a new Helm chart
371. helm pull stable/nginx                            # Download a chart
372. helm plugin list                                  # List installed Helm plugins
373. helm env                                          # Show Helm environment variables
374. helm show values stable/nginx                     # Show default values of a chart
375. helm upgrade --install myapp stable/nginx         # Install or upgrade release
```

