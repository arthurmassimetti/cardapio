# Cardápio

Página de endereço fixo do cardápio. Ela só redireciona: o cardápio de verdade roda em outro aparelho,
cujo endereço na internet muda de vez em quando.

- `index.html`: lê `destino.json`, confere se o cardápio responde e redireciona. Se não responder, avisa e tenta de novo.
- `destino.json`: endereço atual do cardápio. É atualizado automaticamente pelo próprio aparelho.
