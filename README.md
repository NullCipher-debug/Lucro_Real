# 💰 LUCRO REAL - Calculadora para Motorista de App e Motoboy

> Descubra quanto sobra de verdade no fim do dia. 100% local, sem rastro e sem salvar dados.

![Status](https://img.shields.io/badge/status-online-brightgreen)
![Privacidade](https://img.shields.io/badge/privacidade-100%25%20local-blue)
![Feito para](https://img.shields.io/badge/feito%20para-motorista%20e%20motoboy-black)

### [➡️ Acesse a Calculadora Ao Vivo] https://projetos.nullcipher.site/lucroreal/

---

### 📸 Preview do Projeto

<div align="center">
 <img width="1317" height="813" alt="Captura de tela 2026-10-09 004113" src="https://github.com/user-attachments/assets/cb4eb0c6-2b79-47ee-bd91-00528c6c4cd2" />
  <p><i>Interface escura, cálculo em tempo real e foco total no lucro líquido</i></p>
</div>

---

### 📖 Sobre o Projeto

Todo motorista de app e motoboy sabe quanto FATUROU, mas poucos sabem quanto LUCROU de verdade.

O **Lucro Real** foi criado para acabar com essa conta de cabeça. Você insere o faturamento, KM rodado e seus gastos, e ele te mostra na hora seu lucro líquido, lucro por KM e lucro por hora.

**Diferencial:** Nenhum dado é enviado para servidor. Todo cálculo roda no seu navegador. Privacidade total para quem roda na rua.

### ✨ Funcionalidades

- [x] **Dados da Rodada:**
    - Faturamento bruto do dia (R$)
    - KM rodado
    - Horas trabalhadas (opcional) para calcular R$/hora
- [x] **Cálculo Automático de Combustível:**
    - Consumo (km/l) e Preço do combustível (R$/L)
    - Fórmula: `(km / consumo) * preço = custo combustível`
- [x] **Gastos Extras Dinâmicos:**
    - Adicione alimentação, internet, aluguel da moto, etc.
    - Botão + Adicionar e remoção individual
- [x] **Reserva Inteligente:** Checkbox para reservar 10% para manutenção (pneu, óleo, freio e imprevistos)
- [x] **Resultado em Tempo Real:** Painel lateral que atualiza enquanto você digita
- [x] **Exportação:** Gerar Resumo, Baixar PDF e Baixar TXT para controle diário
- [x] **Segurança:** `Cálculo local • sem envio de dados`

### 🧮 Fórmulas Usadas


Custo Combustível = (KM Rodado / Consumo) * Preço do Litro
Lucro Líquido = Faturamento Bruto - (Combustível + Gastos Extras + Reserva Manutenção)
Lucro / KM = Lucro Líquido / KM Rodado
Lucro / Hora = Lucro Líquido / Horas Trabalhadas

Code

### 🛠️ Tecnologias

- **Frontend:** HTML, CSS, JavaScript / Next.js + Tailwind CSS
- **Lógica:** Cálculos 100% em JavaScript no client-side
- **Exportação:** jsPDF para gerar PDF
- **Design:** Interface dark mode, foco em UX para mobile

### 🚀 Como Rodar Localmente

```bash
# 1. Clone o projeto
git clone https://github.com/NullCipher-debug/Lucro_Real

# 2. Entre na pasta
cd lucro-real

# 3. Se for HTML puro, só abrir o index.html
# Se for Next.js / React:
npm install
npm run dev

16 linhas ocultas
🗺️ Roadmap - Próximas Funcionalidades
 Histórico de corridas por semana/mês
 Cálculo de média de ganho por app (Uber, 99, iFood, etc)
 Modo PWA para instalar no celular do motorista
 Comparativo: Moto vs Carro vs Elétrica
👨‍💻 Autor
Feito por Alife para quem vive na pista.
Se esse projeto te ajudou a entender seu lucro real, deixa uma ⭐ no repositório.

Licença: MIT - Pode usar, copiar e melhorar à vontade.



