# logstash-opensearch-opensearchdashboard

```
# Clone repository
git clone [repo-url]
cd docker-opensearch-logging

# Create log directory
mkdir -p logs

# Add test log
echo "$(date '+%Y-%m-%d %H:%M:%S') INFO Test message" > logs/application.log

# Start services
docker-compose up -d
```
