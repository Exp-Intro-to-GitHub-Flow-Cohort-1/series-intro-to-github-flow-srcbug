<!--
  <<< Notas do autor: Passo 3 >>>
  Apenas uma nota histórica: a versão anterior desse passo força o aluno
  a escrever uma descrição de pull request,
  verificar se `main` era quem de fato recebe a ramificação
  e se o arquivo estava nomeado corretamente.
-->

## Passo 3: Abrir uma solicitação de mescla (pull request)

_Ótimo trabalho criando esse commit! :sparkles:_

Agora que você criou uma alteração para o projeto e criou um commit, é hora de compartilhar sua proposta de alteração em uma solicitação de mescla, pull request!

**O que é um pull request?**: Colaboração acontece em um _[pull request](https://docs.github.com/pt/get-started/quickstart/github-glossary#pull-request)_. O pull request mostra as alterações realizadas em sua ramificação para outras pessoas e permite que as pessoas aceitem, rejeitem, ou sugiram alterações adicionais a sua ramificação. Em uma comparação lado a lado, esse pull request irá manter as alterações que você realizou em sua ramificação (branch) e propor a aplicação delas à ramificação principal do projeto, `main`. Para mais informações sobre pull requests, veja "[Sobre Solicitação de pull](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)".

### :keyboard: Atividade: Crie uma solicitação de mescla (pull request)

Você deve ter notado após o commit que uma mensagem foi criada indicando o envio de suas alterações a sua ramificação e disponibilizando um botão que diz **Compare & pull request**.

![Captura de tela da mensagem e botão](/images/compare-and-pull-request.png)

Para criar um pull request automaticamente, clique em **Compare & pull request**, e então pule para o passo 6, logo abaixo. Se você não clicar no botão, as instruções abaixo irão te guiar durante as configurações manuais de solicitação de pull.

1. Clique na aba **Pull requests** no menu de cabeçalho do seu repositório.
2. Clique em **New pull request**.
3. No drop-down **base:**, tenha certeza que **main** foi selecionado.
4. Selecione o drop-down **compare:**, e clique em `my-first-branch`.

   <img alt="captura de tela mostrando ambas as seleções de ramificação" src="/images/pull-request-branches.png" />

5. Clique em **Create pull request**.
6. Digite um título para sua solicitação. Por padrão, o título será automaticamente o nome da ramificação. Para esse exercício, vamos editar esse campo de texto para dizer `Adiciona meu primeiro arquivo`.
7. O próximo campo te auxilia a disponibilizar uma descrição das alterações realizadas por você. Aqui, você pode adicionar uma descrição do que você criou/alterou até o momento. Como um lembrete, você: criou uma nova ramificação, um novo arquivo e realizou um novo commit.

   <img alt="captura de tela mostrando o pull request" src="/images/Pull-request-description.png" />

8. Clique em **Create pull request**. Você será automaticamente redirecionado para sua nova solicitação de pull.
9. Espere por 20 segundos e então recarrega a página (a que você está seguindo as instruções da aula). [GitHub Actions](https://docs.github.com/pt/actions) irá automaticamente atualizar para o próximo passo.

   **Nota**: Você talvez veja o GitHub Actions sendo executado na aba com a solicitação de pull aberta! A imagem abaixo mostra uma linha que talvez você veja em sua solicitação após o Action finalizar a execução.

   <img alt="captura de tela de um exemplo de uma linha de ação" src="/images/Actions-to-step-4.png"/>
