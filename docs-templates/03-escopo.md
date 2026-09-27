# 3.1 Requisitos Funcionais

| ID | Requisito | Critério de Aceite |
|---|---|---|
| RF-001 | O aplicativo deve possuir um botão de "Saída Rápida" visível em todas as telas que redirecione imediatamente para o Google ou uma página neutra | Ao tocar no botão de Saída, a aplicação fecha o conteúdo atual em menos de 1 segundo e exibe uma tela comum. |
| RF-002 | O sistema deve fornecer um diretório com contatos de emergência (Polícia, Central de Atendimento a Mulher, Delegacias) | Os números devem ser exibidos com opção de discagem rápida mesmo com sinal de rede instável |
| RF-003 | O aplicativo deve exibir um guia informativo estruturado sobre os tipos de violência (física, psicológica, moral, patrimonial e sexual) e a Lei Maria da Penha. | A usuária consegue navegar elos tópicos informativos de forma intuitiva, discreta e com linguagem acessivel. |
| RF-004 | O sistema deve permitir que a usuária registre de forma protegida relatos ou evidências (fotos e áudios) armazenados com criptografia logal | Os arquivos salvos exigem autenticação PIN para visualização no dispositivo |
| RF-005 | O aplicativo deve conter uma seção de "Orientações Jurídicas e Direitos" explicando o passo a passo para solicitar medidas protetivas de urgência | O conteúdo deve detalhar de forma clara e objetiva o que a vítima deve fazer ao chegar a uma delegacia |
| RF-006 | O sistema deve permitir ocultar o histórico de navegação ou desativar notificações push para preservar a segurança da usuária | As configurações de privacidade devem ser acessíveis rapidamente na tela inicial |
| RF-007 | O aplicativo deve disponibilizar um mapa ou lista de órgãos de apoio a mulher na região. | O sistema exibe os endereços e telefones de atendimento mais próximos com base na permissão de localização (opcional) |
| RF-008 | O sistema deve permitir que a usuária configure uma lista de contatos de confiança para alertas rápidos | Os contatos podem ser cadastrados e acionados de maneira discreta em situações de risco iminente. |

---

# 3.3 Casos de Uso

## UC-001: Adicionar o botão de saída rápida.
- **Ator:** Usuária em situação de risco ou vulnerabilidade
- **Pré-condição:** Estar navegando em qualquer tela do aplicativo.
- **Fluxo Principal:**
  1. A usuária toca no ícone de saída rápida localizado no topo da tela
  2. O sistema imediatamente oculta a interface atual do aplicativo.
  3. O sistema abre o navegador padrão direcionando para um site neutro.
- **Fluxo Alternativo:** Se a usuária reabrir o aplicativo posteriormente, o sistema pode solicitar uma senha de desbloqueio para proteger a privacidade dos dados.

## UC-002: Consultar Direitos e Canais de Denúncia
- **Ator:** Mulher buscando informação ou apoio
- **Pré-condição:** O aplicativo estar instalado e aberto no dispositivo móvel
- **Fluxo Principal:**
  1. A usuária seleciona a opção "Ajuda e Direitos" no menu principal.
  2. Escolhe entre as categorias (ex: "Onde denunciar", "Medidas protetivas", "Tipos de violência")
  3. O sistema exibe as informações detalhadas e os botões de ligação direta para o 180 ou 190.
- **Fluxo Alternativo:** Caso o aparelho esteja sem internet, o sistema carrega o conteúdo salvo em cache/offline para a seção de emergência e telefones úteis.

---

# 3.4 Fora de Escopo
<!-- 3 a 5 itens que o projeto explicitamente NÃO vai fazer -->
-
-
-
