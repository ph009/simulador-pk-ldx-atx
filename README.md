# Simulador PK · Lisdexamfetamina 30 mg + Atomoxetina 80 mg

Site educacional de página única (HTML + CSS + JS, sem backend). Simula em tempo real a farmacocinética da combinação de lisdexamfetamina (Venvanse) 30 mg e atomoxetina 80 mg, a partir de parâmetros de bulas da FDA e de estudos publicados.

**Abrir:** `index.html` no navegador, ou a versão publicada no GitHub Pages.

## O que tem
- Gráfico de concentração plasmática 0–48 h (LDX intacta, d-anfetamina, atomoxetina) com marcador "AGORA", zoom e pan
- Toggle CYP2D6 (metabolizador extensivo × pobre), modo multi-dose, efeito de alimento e peso
- Painel de estado com fase farmacocinética e resumo em linguagem leiga
- Linha do tempo qualitativa de efeitos, animação da sinapse, painel avançado (ka, k_conv, F, Vd, pH urinário)
- Tabela de parâmetros com fonte de cada valor e lista de referências

## Modelo
- Atomoxetina: 1 compartimento, absorção de 1ª ordem (Bateman), superposição de doses
- Lisdexamfetamina: cadeia intestino → LDX → d-anfetamina → eliminação (solução analítica)
- Valores marcados com "≈" na interface são estimativas ou calibrações

## ⚠ Aviso
Ferramenta **estritamente educacional**, baseada em médias populacionais. **Não é aconselhamento médico** e não deve ser usada para decidir dose ou horário. A variabilidade individual é grande (genética, pH urinário, alimento, outros medicamentos). A combinação LDX + ATX deve ser conduzida apenas sob supervisão médica.
