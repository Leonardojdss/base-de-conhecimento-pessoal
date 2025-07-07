## Criar arquivo sonar-project.properties
```sh
# Root project information
sonar.projectKey=RAG-new-algorithm
sonar.projectName=RAG-new-algorithm
sonar.projectVersion=1.0

# SonarQube Local configuration
sonar.host.url=http://localhost:9000
sonar.token=squ_2983121c98e7af3529611f4eb00ec6a2c7bec61a

# Path to source code
sonar.sources=src

# Path to test files
sonar.tests=tests

# Python-specific properties
sonar.python.coverage.reportPaths=coverage.xml
sonar.language=py
sonar.sourceEncoding=UTF-8

# Exclude files
sonar.exclusions=**/env/**,**/__pycache__/**,**/migrations/**

# Quality Gate configurations
sonar.qualitygate.wait=true
sonar.qualitygate.timeout=300

# Minimum thresholds for Quality Gate
sonar.coverage.threshold=80.0
sonar.duplicated_lines_density.threshold=3.0
sonar.maintainability_rating.threshold=A
sonar.reliability_rating.threshold=A
sonar.security_rating.threshold=A
sonar.security_hotspots_reviewed.threshold=100.0

# Code smell and bug thresholds
sonar.sqale_rating.threshold=A
sonar.bugs.threshold=0
sonar.vulnerabilities.threshold=0
sonar.code_smells.threshold=10
```

## Executar comando
```bash
sonar-scanner
```

OU
```bash
pip install pysonar
pysonar
```
