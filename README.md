### 1. Liste pelo menos 4 problemas arquiteturais que você encontrou no código inicial e explique por que cada um viola o padrão MVC.

# 1: Não houve separação das camadas Model, View e Controller
# 2: Não houve a separação, a criação e a utilização correta dos Blueprints
# 3: Não houve a separação correta dos templates

### 2. Onde ficou a camada Model no seu projeto? Onde ficaram os Controllers? Cite um trecho de cada.

# no arquivo models.py. os controllers ficaram nos routes dos blueprints.

### 3. Por que o url_for e os endpoints precisaram ser ajustados durante a refatoração? Cite um exemplo de mudança que você fez. 

# Especifiquei com . o local certo dos arquivos no blueprints