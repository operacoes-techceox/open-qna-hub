# Versionando configuracoes com segredos

- Commite apenas .env.example (nomes das variaveis)
- .env real no .gitignore, permissao 600
- Em times, avalie Doppler, Vault ou sops+age
- Nunca commite segredos, mesmo em repo privado