## 📈 Prometheus Commands

```bash
376. prometheus --version                                      # Check Prometheus version
377. promtool check config prometheus.yml                      # Validate Prometheus configuration
378. prometheus --config.file=prometheus.yml                   # Start Prometheus
379. prometheus --storage.tsdb.path=data/                      # Define storage path
380. prometheus --web.listen-address=:9090                     # Start Prometheus on a specific port
381. curl http://localhost:9090/api/v1/targets                 # Check active Prometheus targets
382. curl http://localhost:9090/api/v1/status/config           # Fetch Prometheus config
383. curl http://localhost:9090/api/v1/query?query=up          # Run an instant query
384. prometheus --query.lookback-delta=5m                      # Adjust query range
385. prometheus --storage.tsdb.retention.time=15d              # Set data retention
386. prometheus --web.enable-lifecycle                         # Enable reload API
387. curl -X POST http://localhost:9090/-/reload               # Reload configuration
388. systemctl restart prometheus                              # Restart Prometheus service
389. journalctl -u prometheus --no-pager                       # Check Prometheus logs
390. promtool check rules rules.yml                            # Validate recording rules
391. prometheus --storage.tsdb.max-block-duration=2h           # Adjust block duration
392. prometheus --storage.tsdb.no-lockfile                     # Disable lockfile
393. prometheus --enable-feature=remote-write-receiver         # Enable remote write
394. prometheus --web.enable-admin-api                         # Enable admin API
395. promtool query instant http://localhost:9090 "up"         # Query using promtool
```



