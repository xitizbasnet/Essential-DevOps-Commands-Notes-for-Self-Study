## ☸️ Kubernetes (kubectl) Commands

```bash
151. kubectl get nodes                                 # List nodes in the cluster
152. kubectl get pods                                  # List pods
153. kubectl describe pod pod_name                     # Show pod details
154. kubectl logs pod_name                             # Show pod logs
155. kubectl exec -it pod_name -- bash                 # Access a running pod
156. kubectl apply -f file.yaml                        # Apply a YAML file
157. kubectl delete pod pod_name                       # Delete a pod
158. kubectl get svc                                   # List services
159. kubectl get deployments                           # List deployments
160. kubectl scale deployment my-deploy --replicas=5   # Scale deployment
161. kubectl rollout status deployment my-deploy       # Check rollout status
162. kubectl get configmaps                            # List ConfigMaps
163. kubectl get secrets                               # List Secrets
164. kubectl create configmap my-config --from-file=config.txt  # Create ConfigMap
165. kubectl create secret generic my-secret --from-literal=key=value  # Create Secret
166. kubectl port-forward pod/my-pod 8080:80           # Forward port
167. kubectl delete svc my-service                     # Delete a service
168. kubectl expose deployment my-deploy --type=NodePort --port=80  # Expose deployment
169. kubectl get ingress                               # List Ingress resources
170. kubectl describe ingress my-ingress               # Show Ingress details
171. kubectl get namespaces                            # List namespaces
172. kubectl create namespace my-namespace             # Create a namespace
173. kubectl delete namespace my-namespace             # Delete a namespace
174. kubectl config view                               # View kubeconfig settings
175. kubectl get events                                # Show cluster events
176. kubectl drain node_name                           # Drain a node for maintenance
177. kubectl uncordon node_name                        # Mark node as schedulable
178. kubectl taint nodes node_name key=value:NoSchedule  # Taint a node
179. kubectl edit deployment my-deploy                 # Edit deployment config
180. kubectl rollout undo deployment my-deploy         # Rollback deployment
181. kubectl set image deployment/my-deploy container-name=myimage:v2  # Update container image
182. kubectl autoscale deployment my-deploy --min=2 --max=5 --cpu-percent=80  # Autoscale deployment
183. kubectl get hpa                                   # Show Horizontal Pod Autoscaler
184. kubectl cordon node_name                          # Mark node as unschedulable
185. kubectl delete -f resource.yaml                   # Delete a resource using YAML
186. kubectl top nodes                                 # Show node resource usage
187. kubectl top pods                                  # Show pod resource usage
188. kubectl get pv                                    # List PersistentVolumes
189. kubectl get pvc                                   # List PersistentVolumeClaims
190. kubectl logs -f pod_name                          # Stream logs from a pod
191. kubectl exec -it pod_name -- sh                   # Access a pod using sh shell
192. kubectl delete pod --grace-period=0 --force pod_name  # Force delete pod
193. kubectl get all                                   # List all resources
194. kubectl get roles                                 # List roles
195. kubectl get rolebindings                          # List role bindings
196. kubectl get clusterroles                          # List cluster roles
197. kubectl get clusterrolebindings                   # List cluster role bindings
198. kubectl get networkpolicy                         # List network policies
199. kubectl delete node node_name                     # Delete a node
200. kubectl run nginx --image=nginx --restart=Never   # Run a single pod
```
