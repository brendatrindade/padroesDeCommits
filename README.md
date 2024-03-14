<div align="center">  
  <img width=30% src="https://github.com/brendatrindade/Padroes-De-Commits/blob/main/imagem/commitsLogo.png"/>
</div>


# Padrões de Commits

Commits são utilizados para salvar alterações completas no repositório.
O [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/) é uma convenção de mensagens que segue um conjunto de regras para auxiliar os projetos a terem um histórico de commits organizados e bem estruturados.
Os commits realizados compõem a linha do tempo documentada da implementação de um projeto, sendo capaz de identificar quem, quando, o contexto e o tipo de cada alteração realizada.

### Estrutura do commit :
~~~
:emoji: <tipo>(escopo opcional): <descrição> 
[comentário opcional]
[rodapé opcional]
~~~
O emoji é opcional utilizado para agregar identidade visual ao commit. 
O tipo e o escopo são utilizados para contextualizar e a descrição para detalhar o commit.

---

### Tipos

- `init` - O commit initial é o primeiro commit salvo no repositório, contém informações de README e Licenças... (Não inclui alterações em código)
  
- `feat`- O commit **adiciona um novo recurso**.

- `test` - O commit **altera testes** (Seja criando, alterando ou excluindo. Não inclui alterações em código).

- `fix` - O commit **corrige um problema**.

- `docs` - O commit **altera a documentação** (Ex.:Readme do repositório. Não inclui alterações em código ).

- `refactor` - O commit identifica alterações referente a **refatorações que não alterem sua funcionalidade** (code review).

- `style` - O commit **altera formatações de código** (semicolons, trailing spaces, lint... Não inclui alterações em código).
  
- `build` - O commit **modifica arquivos de build e dependências**.

- `perf` - O commit identifica quaisquer alterações de código que estejam relacionadas a **performance**.

- `chore` - O commit **atualiza** tarefas de build, configurações de administrador, pacotes, entre outros (Ex.: adicionar um pacote no gitignore. Não inclui alterações em código).

- `raw` - O commit identifica alterações relacionadas a arquivos de configurações, dados, features, parametros.

- `ci` -  O commit identifica alterações relacionadas a **integração contínua**.

- `revert` - O commit reverte um commit realizado anteriormente. Deve conter o ID do commit revertido e a descrição da reversão.

### Escopo
Contextualiza o commit, podendo informar branches, arquivos ou funções.

### Descrição
Identifica as alterações, texto na segunda pessoa do presente (imperativo).
Ex.: Adiciona (funcionalidade) / Remove (funcionalidade) / Corrige (funcionalidade) / etc.

### Comentário
Explica o que e por que das alterações, não como. Permitindo identificar a funcionalidade das alterações.
Descreve brevemente o conteúdo do commit, podendo citar quais foram as alterações no código, seu objetivo, impactos e instruções.

### Rodapé
Pode ser utilizado para assinatura referente a autoria, alertar e informar incompatibilidade com a versão anterior.

---

## Padrões

<table>
  <thead>
    <tr>
      <th>Tipo do commit</th>
      <th>Emoji</th>
      <th>Palavra-chave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Commit inicial</td>
      <td>🎉 <code>:tada:</code></td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td>✨ <code>:sparkles:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td>📚 <code>:books:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td>🐛 <code>:bug:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td>🚧 <code>:construction:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Estilização de interface</td>
      <td>💄 <code>:lipstick:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Refatoração</td>
      <td>♻️ <code>:recycle:</code></td>
      <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Testes</td>
      <td>🧪 <code>:test_tube:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Mover/Renomear</td>
      <td>🚚 <code>:truck:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Comentários</td>
      <td>💡 <code>:bulb:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Configuração</td>
      <td>🔧 <code>:wrench:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Alterações de revisão de código</td>
      <td>👌 <code>:ok_hand:</code></td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Tag de versão</td>
      <td>🔖 <code>:bookmark:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td>⚡ <code>:zap:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
      <td>Texto</td>
      <td>📝 <code>:pencil:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Dados</td>
      <td>🗃️ <code>:card_file_box:</code></td>
      <td><code>raw</code></td>
    </tr>
    <tr>
      <td>Animações e transições</td>
      <td>💫 <code>:dizzy:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td>🚀 <code>:rocket:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td>🧱 <code>:bricks:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Tratamento de erros</td>
      <td>🥅 <code>:goal_net:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Responsividade</td>
      <td>📱 <code>:iphone:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td>🔒️ <code>:lock:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>🔍️ <code>:mag:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Adicionando um teste</td>
      <td>✅ <code>:white_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>   
    <tr>
      <td>Adicionando uma dependência</td>
      <td>➕ <code>:heavy_plus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td>🔥 <code>:fire:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Removendo uma dependência</td>
      <td>➖ <code>:heavy_minus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Revertendo mudanças</td>
      <td>💥 <code>:boom:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Teste de aprovação</td>
      <td>✔️ <code>:heavy_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Mudanças no processo de CI </td>
      <td>💚 <code>:green_heart:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td> Alteração no ambiente Docker </td>
      <td>🐳 <code>:whale:</code></td>
      <td></td>
    </tr>
    <tr>
      <td> Reversão de um commit </td>
      <td>⏪ <code>:rewind:</code></td>
      <td><code>revert</code></td>
    </tr>
    <tr>
      <td>Acessibilidade</td>
      <td>♿ <code>:wheelchair:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tipagem</td>
      <td>🏷️ <code>:label:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Package.json em JS</td>
      <td>📦 <code>:package:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Atualizando a versão de um submódulo</td>
      <td>⬆️ <code>:arrow_up:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Retrocedendo a versão de um submódulo</td>
      <td>⬇️ <code>:arrow_down:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Lista de ideias (tasks)</td>
      <td>🔜 <code> :soon: </code></td>
      <td></td>
    </tr>
  </tbody>
</table>

Mais [emojis](https://gitmoji.dev/).
#

### Boa prática 
Realizar o commit de uma funcionalidade por vez, independente do número de arquivos alterados. 
O programa deve permanecer totalmente funcional a cada commit, permitindo reverter alterações caso necessário com facilidade.

#
[Documentação Git-Commit](https://git-scm.com/docs/git-commit/pt_BR)
