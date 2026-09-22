╔══════════════════════════════════════╗
║          MENU PRINCIPAL              ║
╚══════════════════════════════════════╝
  [1] 🔑 Gerar hash de uma senha
  [2] 🔍 Buscar senha com wordlist (1 hash)
  [3] 💥 Brute force (variações automáticas)
  [4] 📋 Verificar múltiplos hashes
  [5] 📊 Estatísticas da wordlist
  [0] 🚪 Sair

Escolha (0-5): 1          ← Gerar hash
  senha: minhaSenha123
  algoritmo: sha256
  → hash: a1b2c3d4...

Escolha (0-5): 2          ← Buscar com wordlist
  hash: a1b2c3d4...
  algoritmo: sha256
  wordlist: wordlist.txt
  → ✅ SENHA ENCONTRADA!

Escolha (0-5): 3          ← Variações automáticas
  senha base: admin
  hash: ...
  → Testa admin, admin1, admin123, admin@2025...

Escolha (0-5): 4          ← Múltiplos hashes
  (cole vários hashes de uma vez)
  → Resultado para cada hash

Escolha (0-5): 5          ← Estatísticas
  → Total, duplicadas, distribuição, top 10...
