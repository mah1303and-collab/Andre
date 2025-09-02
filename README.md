# Desafio: Cartas Super Trunfo

## Descrição
Jogo estilo Super Trunfo em linha de comando. O jogador enfrenta uma CPU; cada rodada, o jogador/CPU escolhe um atributo e compara as cartas.

## Como rodar
1. Clone:
   ```bash
   git clone <URL-do-repositorio>
   cd super-trunfo
   ```
2. Crie ambiente (opcional) e instale dependências:
   ```bash
   python -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   pip install -r requirements.txt
   ```
3. Execute:
   ```bash
   python src/main.py
   ```

## Estrutura
- `src/` — código fonte
- `data/cartas.json` — cartas usadas no jogo
- `tests/` — testes automatizados

## Melhorias possíveis
- Interface web (Flask/React)
- Multiplayer via socket
- Salvamento de estatísticas
- Mais atributos e maior coleção de cartas

## Autor
Seu Nome — suas informações
