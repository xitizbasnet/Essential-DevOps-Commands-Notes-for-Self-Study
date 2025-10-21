## 📊 Monitoring, CI/CD & Security

```bash
396. grafana-server --version                                      # Check Grafana version
397. systemctl start grafana-server                                # Start Grafana
398. systemctl stop grafana-server                                 # Stop Grafana
399. systemctl restart grafana-server                              # Restart Grafana
400. grafana-cli plugins install plugin-id                         # Install Grafana plugin
401. argocd version                                                # Show ArgoCD CLI version
402. argocd login my-argocd.com                                    # Login to ArgoCD
403. argocd app list                                               # List ArgoCD apps
404. argocd app create my-app --repo https://repo.git --path . --dest-server https://k8s --dest-namespace default  # Create app
405. argocd app sync my-app                                        # Sync app
406. argocd app delete my-app                                      # Delete app
407. argocd app rollback my-app 1                                  # Rollback app
408. argocd app get my-app                                         # Get app details
409. argocd app logs my-app                                        # View app logs
410. argocd app history my-app                                     # View app history
411. argocd app diff my-app                                        # Show app diff
412. argocd cluster list                                           # List connected clusters
413. argocd repo list                                              # List repositories
414. argocd repo add https://repo.git --username user --password pass  # Add repository
415. argocd logout                                                 # Logout from ArgoCD
416. gh workflow list                                              # List GitHub Actions workflows
417. gh workflow run my-workflow.yml                               # Run a workflow
418. gh run list                                                   # List workflow runs
419. gh run view 123456                                            # View workflow run
420. gh run cancel 123456                                          # Cancel workflow run
421. gh run watch 123456                                           # Watch workflow run
422. gh secret list                                                # List secrets
423. gh secret set MY_SECRET                                       # Set secret
424. gh variable list                                              # List variables
425. gh variable set MY_VAR --body "value"                         # Set variable
426. gitlab-runner register                                        # Register GitLab runner
427. gitlab-runner start                                           # Start GitLab runner
428. gitlab-runner stop                                            # Stop GitLab runner
429. gitlab-runner restart                                         # Restart GitLab runner
430. gitlab-runner unregister                                      # Unregister GitLab runner
431. gitlab-runner verify                                          # Verify runner
432. gitlab-runner list                                            # List runners
433. gitlab-runner status                                          # Show runner status
434. gitlab-runner logs                                            # View runner logs
435. circleci config validate                                      # Validate CircleCI config
436. circleci local execute -c .circleci/config.yml                # Run job locally
437. circleci setup                                                # Setup CircleCI CLI
438. circleci context list                                         # List contexts
439. circleci context show my-context                             # Show context details
440. circleci namespace list                                       # List namespaces
441. trivy image nginx:latest                                      # Scan Docker image
442. trivy filesystem /path/to/dir                                 # Scan local filesystem
443. trivy config .                                                # Scan IaC configs
444. vault server -dev                                             # Start Vault in dev mode
445. vault kv put secret/mysecret key=value                       # Store secret
446. vault kv get secret/mysecret                                 # Retrieve secret
447. vault login <token>                                           # Authenticate to Vault
448. loki -config.file=loki-config.yml                             # Start Loki
449. curl -X GET 'http://localhost:3100/ready'                     # Check Loki readiness
450. curl -X GET 'http://localhost:3100/loki/api/v1/query?query={app="nginx"}'  # Query logs
451. curl -X GET "localhost:9200/_cat/indices?v"                   # List Elasticsearch indices
452. curl -X GET "localhost:9200/_cluster/health?pretty"           # Check cluster health
453. curl -X GET "localhost:9200/_search?q=nginx&pretty"           # Search logs
454. systemctl restart logstash                                    # Restart Logstash
455. systemctl restart kibana                                      # Restart Kibana
456. fluentd --config fluentd.conf                                 # Start Fluentd
457. fluentd --dry-run --config fluentd.conf                       # Validate Fluentd config
458. htop                                                         # Interactive process viewer
459. iftop                                                        # Monitor network bandwidth
460. iotop                                                        # Monitor disk I/O
461. nc -zv host 80                                               # Check if port is open
462. curl -I http://example.com                                   # Fetch HTTP headers
463. dig example.com                                              # DNS lookup
464. nslookup example.com                                         # DNS lookup (alternative)
465. traceroute example.com                                       # Trace route to host
466. ping example.com                                             # Ping a host
467. nmap -sP 192.168.1.0/24                                      # Network scan
468. telnet host 80                                               # Test TCP connection
469. netcat -zv host 22                                           # Check SSH port
470. systemctl status nginx                                       # Check service status
471. systemctl enable nginx                                       # Enable service at boot
472. systemctl disable nginx                                      # Disable service
473. journalctl -xe                                               # View system logs
474. dmesg | tail                                                 # View kernel logs
475. ip a                                                         # Show IP addresses
476. ip r                                                         # Show routing table
477. ss -tulwn                                                    # Show open ports
478. hostnamectl                                                  # Show hostname info
479. timedatectl                                                  # Show time settings
480. whoami                                                       # Show current user
481. groups                                                       # Show user groups
482. id                                                           # Show user ID info
483. env                                                          # Show environment variables
484. export VAR=value                                             # Set environment variable
485. unset VAR                                                    # Unset environment variable
486. source ~/.bashrc                                             # Reload shell config
487. history | grep ssh                                           # Search command history
488. !45                                                          # Run command #45 from history
489. alias gs='git status'                                        # Create alias
490. unalias gs                                                   # Remove alias
491. which python                                                 # Show path to binary
492. whereis nginx                                                # Locate binary and config
493. locate nginx.conf                                            # Find file by name
494. updatedb                                                    # Update file index
495. man ls                                                       # Show manual page
496. whatis ls                                                    # Show command summary
497. apropos user                                                 # Search man pages
498. help cd                                                      # Show shell help
499. type ls                                                      # Show command type
500. command -v ls                                                # Show command path
```


