## Projeto: ZAP 

### Issue: [#6119 New common getExampleAlerts() method](https://github.com/zaproxy/zaproxy/issues/6119)

## Descrição da Sprint

**Resumo:** O mantenedor do projeto está propondo um novo método a ser implementado em todas as classes de scanner, chamado "getExampleAlerts()". Esse método tem o objetivo de fornecer um alerta de exemplo para ser acessado por um script que irá gerar as páginas de alerta na documentação ([https://www.zaproxy.org/docs/alerts/](https://www.zaproxy.org/docs/alerts/)).

O método construído deve retornar uma lista contendo um exemplo para cada tipo de alerta que a classe pode gerar. A classe escolhida para essa sprint foia a **SourceCodeDisclosureGitScanRule**.

[Pull request relacionado](https://github.com/zaproxy/zap-extensions/pull/4567)
![Zap: Issue 6119](../../assets/zap-issue-6119.png)
