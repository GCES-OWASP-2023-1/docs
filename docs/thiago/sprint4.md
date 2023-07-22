## Projeto: ZAP 

### Issue: [#6119 New common getExampleAlerts() method](https://github.com/zaproxy/zaproxy/issues/6119)

## Descrição da Issue

**Resumo:** O mantenedor do projeto deseja que sejam implementados métodos com o objetivo de fornecer um alerta de exemplo para ser acessado por um script que irá gerar as páginas de alerta na documentação ([https://www.zaproxy.org/docs/alerts/](https://www.zaproxy.org/docs/alerts/)).

![Zap: Issue 6119](../../assets/zap-issue-6119.png)


## O que foi desenvolvido para essa issue?

Realizei correções solicitadas pelos mantenedores do projeto na PR que adiciona a funcionalidade de 'get examples' para a classe de XAspNetVersionScanRule, após as correções solicitdas a PR foi aceita e o Merge foi efetuado. Após o aceite do merge dessa PR, continue nesta mesma issue e inciei o desenvolvimento da funcionalidade de 'get examples' semelhante a que foi desenvolvida anteriormente, mas agora para a classe de XBackendServerInformationLeakScanRule.

[Pull request mergeada](https://github.com/zaproxy/zap-extensions/pull/4625)
<br/>
[Nova pull request aberta](https://github.com/zaproxy/zap-extensions/pull/4677)

