## Descrição da Situação Atual (problema identificado)

O sistema atual apresenta:
- Idioma do HTML configurado como `en` (inglês)
- Título da aba do navegador genérico: "My Web App"
- Cabeçalho da página exibindo "Welcome"

Esses elementos não estão adequados ao público-alvo brasileiro e não seguem a identidade da organização.

---

## Fluxo da Atividade – Maratona de Configuração e Manutenção

1.  **Faça um fork deste repositório**
   - Um integrante do grupo faz o fork e inclui os demais membros como colaboradores.

2. **Crie uma *Issue* neste repositório original (do professor)**
   - A *Issue* será a sua Solicitação de Mudança (RfC).
   - Use o modelo: resumo, mudanças propostas, justificativa e riscos.

3. **Aguarde a aprovação da mudança pelo professor**
   - O professor irá aprovar ou solicitar ajustes diretamente na issue.

4.  **No seu fork, crie as branches:**
   - `develop` a partir da `main`
   - `feature/RfC-XXXX-descricao` a partir da `develop`

5.  **Implemente a mudança na branch `feature/...`**
   - Altere os arquivos indicados (`index.html`)

6. **Faça commits com mensagens claras**
   ```bash
   feat: altera HTML conforme RfC-.....

7. **Validação**
   - A validação da mudança será considerada realizada quando o grupo fizer o merge da branch `feature/...` para `develop`, e posteriormente da `develop` para `main` no repositório do grupo.
   - Essa etapa pode ser registrada em um novo commit ou como comentário em uma issue criada no fork.
   
8.  **Avaliação**
   - Se percorreu todas as etapas do fluxo de mudança
   - Se todos os membros participaram efetivamente
   - Se a mudança atendeu ao requisito solicitado
   - Se foi criado um Pull Request da branch main do fork para o repositório do professor
