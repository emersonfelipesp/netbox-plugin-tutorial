# Tutorial para Desenvolvimento de Plugins

Esse guia procura demonstrar o processo de desenvolvimento de um plugin customizado para o Netbox na versão v3.2 ou maior. Seguindo cada um dos passos descritos, o leitor será capaz de criar um plugin desde o início para o gerenciamento de Listas de Acesso (ACLs) no Netbox, utilizando a maioria dos componentes do framework de plugins do Netbox.

Uma cópia completa do plugin demo criado neste tutorial está disponível no repositório [`netbox-plugin-demo`](https://github.com/netbox-community/netbox-plugin-demo) para ser utilizado de referência. Para a sua conveniência, o código completo correspondente à cada passo do tutorial está salvo como em uma branch específica no repositório demo. Por exemplo, se você quer começar do passo 05, basta mudar para a branch `step04-forms` realizando o checkout.

### Prerequisites

Before attempting to create a plugin, please assess your personal ability. Plugin authors should have reasonable proficiency in the following:

* Python programming
* The [Django](https://www.djangoproject.com/) framework
* REST API fundamentals (where applicable)
* Installing, configuring, and using NetBox

### Contents

* [Step 1: Initial Setup](/tutorial/step01-initial-setup.md) :arrow_left: Start here!
* [Step 2: Models](/tutorial/step02-models.md)
* [Step 3: Tables](/tutorial/step03-tables.md)
* [Step 4: Forms](/tutorial/step04-forms.md)
* [Step 5: Views](/tutorial/step05-views.md)
* [Step 6: Templates](/tutorial/step06-templates.md)
* [Step 7: Navigation](/tutorial/step07-navigation.md)
* [Step 8: Filter Sets](/tutorial/step08-filter-sets.md)
* [Step 9: REST API](/tutorial/step09-rest-api.md)
* [Step 10: GraphQL API](/tutorial/step10-graphql-api.md)

### Reference

* [NetBox Plugin Development Documentation](https://netbox.readthedocs.io/en/feature/plugins/development/)

### Getting Help

If you run into any snags working through the tutorial, please join us in the **#netbox** channel on the [NetDev Community Slack](https://netdev.chat/) for help.

### Feedback and Issues

If you happen to uncover an error or discrepancy in the tutorial, please be sure to [open an issue](https://github.com/netbox-community/netbox-plugin-tutorial/issues/new/choose) so that it can be documented and fixed.

