# Quality Gate Configuration for RAG-new-algorithm
# Este arquivo define os critérios mínimos que o projeto deve atender

# ========================================
# CONFIGURAÇÕES DE QUALITY GATE
# ========================================

# 1. COBERTURA DE CÓDIGO
# Mínimo: 80% de cobertura de linhas
Coverage on New Code: >= 80%
Coverage: >= 80%

# 2. DUPLICAÇÃO DE CÓDIGO
# Máximo: 3% de linhas duplicadas
Duplicated Lines on New Code: <= 3%
Duplicated Lines: <= 3%

# 3. MAINTAINABILITY (Manutenibilidade)
# Rating A (melhor) a E (pior)
Maintainability Rating on New Code: A
Maintainability Rating: A

# 4. RELIABILITY (Confiabilidade)
# Rating A (melhor) a E (pior)
Reliability Rating on New Code: A
Reliability Rating: A

# 5. SECURITY (Segurança)
# Rating A (melhor) a E (pior)
Security Rating on New Code: A
Security Rating: A

# 6. SECURITY HOTSPOTS
# 100% dos hotspots de segurança devem ser revisados
Security Hotspots Reviewed on New Code: >= 100%
Security Hotspots Reviewed: >= 100%

# 7. BUGS E VULNERABILIDADES
# Zero bugs e vulnerabilidades permitidos
Bugs on New Code: = 0
Bugs: = 0
Vulnerabilities on New Code: = 0
Vulnerabilities: = 0

# 8. CODE SMELLS
# Máximo de 10 code smells
Code Smells on New Code: <= 10
Code Smells: <= 10

# ========================================
# COMO APLICAR ESTAS CONFIGURAÇÕES
# ========================================

# OPÇÃO 1: Via Interface Web do SonarQube
# 1. Acesse: http://localhost:9000
# 2. Vá em: Quality Gates → Create
# 3. Nome: "RAG-Quality-Gate"
# 4. Adicione as condições acima
# 5. Associe ao projeto RAG-new-algorithm

# OPÇÃO 2: Via API do SonarQube
# Execute os comandos curl para criar o Quality Gate programaticamente

# OPÇÃO 3: Via configuração no projeto
# As configurações já foram adicionadas no sonar-project.properties
