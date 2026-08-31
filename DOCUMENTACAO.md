# Documentação técnica

## Arquitetura

O projeto é uma coleção sequencial de notebooks independentes. Cada arquivo contém enunciados, implementações, explicações e saídas. Não há serviço web, banco de dados, credenciais ou etapa de deploy.

## Dependências

- Labs 01 e 02: NumPy e Matplotlib.
- Labs 03 e 04: NumPy, Matplotlib e PyTorch; o Lab 03 também usa scikit-learn.
- Lab 05: NumPy, Matplotlib, scikit-learn e TensorFlow.

As versões em requirements.txt estabelecem uma base reproduzível. PyTorch e TensorFlow podem exigir instalação específica para aceleração por GPU.

## Fluxo de execução

Execute os notebooks na ordem numérica para acompanhar a evolução conceitual. Cada notebook permanece executável de forma independente. As saídas existentes são evidências da última execução, não uma garantia de resultados idênticos.

## Segurança e privacidade

Os notebooks foram verificados antes da publicação. Não foram encontrados tokens, senhas, chaves de API, e-mails ou caminhos pessoais. Não adicione datasets privados, credenciais ou arquivos de ambiente ao repositório.

## Alterações rápidas

- Novo laboratório: adicione o notebook em notebooks/ com prefixo numérico e inclua uma linha na tabela do README.
- Nova biblioteca: adicione a dependência a requirements.txt e registre seu uso nesta documentação.
- Nova execução: revise as saídas antes do commit para não publicar dados locais ou conteúdo excessivo.

## Diagnóstico

- ModuleNotFoundError: confirme que o kernel usa o mesmo ambiente em que requirements.txt foi instalado.
- Falta de memória: reinicie o kernel ou reduza épocas e lotes quando a atividade permitir.
- GPU indisponível: use CPU ou instale builds compatíveis com seu sistema.
- Resultados diferentes: confira sementes, versões, dispositivo e ordem das células.

## Histórico

- Estrutura inicial com os Labs 01–05, nomes padronizados e documentação central.


