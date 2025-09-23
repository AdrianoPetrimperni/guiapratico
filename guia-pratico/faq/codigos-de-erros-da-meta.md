# Códigos de erros da Meta

## Códigos de erros da Meta

### Erro 131049 - Envio de Template Messenger de Marketing <a href="#o8rw4y96ay9d" id="o8rw4y96ay9d"></a>

<figure><img src="https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FxckEHL5DdqhOAA3x1KMi%2Fimage.png?alt=media&#x26;token=4b6f412b-21a1-464e-9a71-c38708a7417b" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

Meta recusou enviar esse modelo (Marketing) para manter o engajamento saudável do ecossistema.

Tente novamente mais tarde ou utilize um modelo do tipo Utilidade.

Para saber mais acesse esse link: [https://developers.facebook.com/docs/whatsapp/cloud-api/guides/send-message-templates#user-marketing-template-message-limits](https://developers.facebook.com/docs/whatsapp/cloud-api/guides/send-message-templates#user-marketing-template-message-limits)
{% endhint %}

Ao receber este código de erro, não tente enviar a mensagem novamente. Esse problema está relacionado ao limite de mensagens de marketing que o destinatário recebeu. Tente enviar uma mensagem do tipo utilidade ou espere um tempo maior para enviar mensagens novamente, já que o limite talvez esteja em vigor por diferentes períodos.

**Porque esse erro ocorre:**

Esse erro ocorre quando você tenta enviar um modelo de mensagem para iniciar ou reiniciar um atendimento. Vale ressaltar que isso **não é um erro da Táime Pro**, mas sim uma ação da **Meta**, sobre a qual não temos controle.

Em alguns casos, a Meta decide que um número de telefone já recebeu muitas mensagens de **marketing** e, como medida para manter um ambiente saudável para os usuários do WhatsApp, ela **interrompe temporariamente o envio de novas mensagens de marketing** para esse número.

Infelizmente, não podemos evitar essa ação da Meta, mas ela é aplicada com o objetivo de preservar uma boa experiência para os usuários do WhatsApp.

**Veja algumas soluções para esse erro:**

Embora o bloqueio temporário de mensagens de marketing pela Meta seja uma medida que não podemos controlar diretamente, há algumas estratégias que você pode adotar para minimizar o impacto e garantir que a comunicação com seus clientes continue fluindo de forma eficiente:

* **Varie os tipos de mensagem**: Ao invés de enviar apenas mensagens de marketing, utilize outro tipo de mensagens, como de **Utilidade.**
* **Ajuste o volume de envio**: Evite o envio excessivo de mensagens do tipo marketing em um curto período de tempo para o mesmo número. Isso ajuda a reduzir a chance de a Meta bloquear os envios futuros.
* **Aguarde o desbloqueio**: Se um número for bloqueado, aguarde o período determinado pela Meta (geralmente de algumas horas a dias) para que o envio de mensagens seja liberado novamente.

### Erro 131056 - Limite de volume de envios de mensagens atingido <a href="#afwfmfslcv85" id="afwfmfslcv85"></a>

![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FUo0ct8JpK0OuguQsGZOu%2F1.png?alt=media)

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

Foram enviadas muitas mensagens do número de telefone do remetente para o mesmo número de telefone do destinatário em um curto período.
{% endhint %}

**Porque esse erro ocorre:**

O erro de envio de mensagens acontece principalmente quando muitas mensagens são enviadas para o mesmo contato em um curto período de tempo.

**A plataforma está funcionando corretamente**, mas a **Meta** (responsável pelo WhatsApp) pode bloquear temporariamente o envio de mensagens de marketing se identificar que um número está recebendo um volume excessivo de mensagens em pouco tempo.

Isso ocorre porque a Meta tem o objetivo de evitar que os usuários do WhatsApp recebam muitas mensagens de marketing de forma indiscriminada, o que pode prejudicar a experiência deles na plataforma. Quando um número de telefone recebe muitas mensagens desse tipo, a Meta decide pausar o envio de novas mensagens para aquele número por um tempo, para manter um ambiente mais saudável para todos os usuários.

**Veja algumas soluções para esse erro:**

* **Reduza a quantidade de mensagens enviadas para cada contato**: Evite enviar muitas mensagens de marketing para o mesmo número em um curto período de tempo. Dê intervalos entre os envios e tente não enviar uma quantidade excessiva de mensagens de uma só vez. Isso ajuda a evitar que a Meta bloqueie temporariamente o envio.
* **Varie os tipos de mensagens enviadas**: Em vez de enviar apenas mensagens de marketing, alterne para outros tipos de mensagens, como **mensagens do tipo utilidade**. A Meta tem regras mais flexíveis para esses tipos de comunicação e elas não costumam ser bloqueadas com a mesma frequência.
* **Monitore a entrega das mensagens**: Acompanhe o status de entrega das suas mensagens na plataforma Táime Pro. Se você perceber que está ocorrendo o bloqueio de envios, tente reduzir o volume de mensagens e aguarde o período de desbloqueio automático da Meta.

### Erro 130472 - Experimento da Meta <a href="#cdbuvqduo7ju" id="cdbuvqduo7ju"></a>

![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FIudjV1EbjNwLvSyG8aUv%2F2.png?alt=media)

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

O número do usuário faz parte de um experimento do WhatsApp, não é possível iniciar esta conversa. Escolha uma das opções abaixo.
{% endhint %}

**Porque esse erro ocorre:**

Esse erro faz parte de um **experimento da Meta** que está sendo aplicado a **1% dos usuários** do WhatsApp. Durante esse experimento, a Meta está testando uma nova medida para limitar quem pode iniciar conversas com empresas no WhatsApp.

Esse erro indica que o WhatsApp não permite iniciar conversas com determinados usuários utilizando modelos de mensagem do tipo **Marketing**. No entanto, é possível iniciar uma conversa com os participantes do experimento utilizando modelos de mensagem do tipo **Utilidade**.

A Meta tomou essa decisão como parte de uma estratégia para **melhorar a experiência dos usuários** e evitar o envio excessivo de mensagens não solicitadas.

**Veja algumas soluções para esse erro:**

* **Utilize um modelo de mensagem do tipo Utilidade**: Inicie a conversa utilizando um modelo apropriado para esse propósito.
* **Aguarde o usuário iniciar o contato**: Caso encontre esse erro, a melhor alternativa é esperar que o usuário envie uma mensagem para sua empresa. Após o primeiro contato, você poderá responder e continuar a comunicação normalmente.

Em resumo, o erro 130472 é um teste da Meta e, por enquanto, não há muito que possa ser feito além de aguardar que o usuário entre em contato. Essa medida está sendo aplicada a um número pequeno de usuários, e a Meta pode ajustar ou remover essa restrição no futuro.

### **Erro 131042 - META**

<figure><img src="https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2F8jHTTjeksi4esKsiUyz0%2F3.png?alt=media" alt="" width="503"><figcaption></figcaption></figure>

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

A Meta recusou enviar sua mensagem, isso está relacionado à tentativa de faturar conversas no cartão de crédito.

Saiba como adicionar um cartão de crédito neste link: [https://web.facebook.com/business/help/488291839463771?\_rdc=1&\_rdr#](https://web.facebook.com/business/help/488291839463771?_rdc=1&_rdr)
{% endhint %}

**Porque esse erro ocorre:**

O **Erro 131042** ocorre quando a Meta enfrenta dificuldades para processar o pagamento por meio do cartão cadastrado na conta do **portfólio empresarial**. Esse problema geralmente está relacionado a um bug interno no sistema da Meta, que impede a realização do débito mesmo quando o cartão está válido e funcional.

**Veja como solucionar esse erro:**

* **Confirme os dados do cartão:**
  * Verifique se as informações do cartão cadastradas na Business Manager estão corretas.
  * Certifique-se de que o cartão possui saldo suficiente para cobrir o débito.
  * No **Gerenciador de Negócios**, siga estas etapas para resolver falhas de pagamento:

1. Acesse **Contas** > **Contas do WhatsApp** > **Configurações de pagamento**.
2. Verifique o saldo disponível. Por exemplo, se houver um saldo de **8 dólares**, tente realizar o pagamento desse valor.
3. Caso o pagamento do valor total não seja concluído devido a uma falha, ajuste o valor manualmente:
   * Edite o campo de pagamento e insira um valor menor, como **7 dólares**.
4. Realize o pagamento com o valor reduzido. Assim que a transação for reconhecida, a Meta liberará o envio de mensagens normalmente.

* **Atualize o método de pagamento:**
  * No **Gerenciador de Negócios**, acesse **Contas** > **Contas do WhatsApp** > **Configurações de pagamento**.
  * Na página **Configurações de pagamento**, clique em **Adicionar forma de pagamento.**
  * Siga as instruções para adicionar as informações de pagamento e clique em **Avançar**.
  * Adicione as **informações do cartão** e clique em **Salvar**.

### Erro 131026 - Número não registrado no Whats <a href="#sirpmrgu535p" id="sirpmrgu535p"></a>

![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FPwFgrwJUv5Vjxn7qN0Bb%2F4.png?alt=media)

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

Não foi possível entregar a mensagem. O número de telefone do destinatário não está registrado no WhatsApp ou o destinatário não aceitou os novos Termos de Serviço e a nova Política de Privacidade.
{% endhint %}

**Porque esse erro ocorre:**

O **Erro 131026** ocorre quando uma tentativa de enviar uma mensagem para um número de WhatsApp falha porque o número informado **não está registrado no WhatsApp**. Isso significa que o destinatário não tem uma conta ativa vinculada ao número fornecido.

As causas mais comuns são:

1. **Número sem conta no WhatsApp**:\
   O número não está associado a nenhuma conta ativa no WhatsApp.
2. **Mudança de número pelo usuário**:\
   O destinatário pode ter alterado o número registrado no WhatsApp e não atualizou a informação com sua empresa.
3. **Erro ao digitar o número**:\
   O número foi inserido incorretamente, com dígitos a mais, a menos ou no formato errado.
4. **Desativação da conta pelo usuário**:\
   O destinatário pode ter desativado a conta temporária ou permanentemente.

**Veja algumas soluções para esse erro:**

* **Verifique o número informado**:
  * Tente realizar uma chamada para o número no WhatsApp, seja pelo aplicativo ou utilizando o link **wa.me/\[número]**, para confirmar se o número está registrado no WhatsApp.
  * Certifique-se de que o número está correto e no formato internacional, incluindo o código do país (ex.: +55 para Brasil).
  * Verifique se o número foi editado, ex: inserir o 9.
  * Confirme com o cliente se o número registrado é o mesmo utilizado no WhatsApp.

Se o problema persistir, você pode realizar um segundo passo para verificar se a falha está relacionada ao **Template de Mensagem (TM)** ou ao número:

1. **Envie a mesma TM para outro número ativo no WhatsApp**:
   * Escolha um número que você sabe que está registrado no WhatsApp.
   * Envie a mesma mensagem (TM).
   * **Se a mensagem for enviada com sucesso**: O problema está no número original (não registrado no WhatsApp).
   * **Se a mensagem não for enviada**: O problema pode estar na TM (modelo de mensagem) ou na configuração da conta. Tente enviar outro TM (modelo de mensagem).

### Erro 131000 - Erro desconhecido <a href="#e0ukwxsjis3v" id="e0ukwxsjis3v"></a>

![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FUmjBEjNVsWF6cTSCuM2s%2F5.png?alt=media)

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

Falha ao enviar a mensagem devido a um erro desconhecido.
{% endhint %}

**Por que esse erro acontece?**

O **Erro 131000** ocorre quando há um problema técnico ao tentar enviar uma mensagem pelo WhatsApp através da API da Meta. Geralmente, este erro está relacionado a configurações incorretas, falhas de comunicação entre a plataforma da Meta e o serviço utilizado, ou até mesmo instabilidades nos servidores da Meta.

**Veja algumas soluções para esse erro:**

* **Verifique** se há relatos de instabilidade ou manutenção no [**status da API da Meta**](https://metastatus.com/)
* Verifique a conexão com a sua **internet**.
* Tente enviar outra mensagem.

{% hint style="info" %}
**Observação:** Caso esse erro ocorra logo após a conexão do número na API Oficial, exclua todas as informações relacionadas no **portfólio empresarial** e conecte o número novamente.
{% endhint %}

### Erro 135000 - Falha ao enviar mensagem <a href="#jrbec5iwehcn" id="jrbec5iwehcn"></a>

![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FW4OX47jjbiPAqkAKmSIP%2F1.png?alt=media\&token=0e1ae6b9-3ab7-48a4-b260-1c8cf1c36f3a)

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

Falha ao enviar a mensagem devido a um erro desconhecido com seus parâmetros de solicitação.
{% endhint %}

**Por que esse erro acontece?**

O erro 135000 ocorre quando o atendente tenta enviar um modelo de mensagem em um atendimento, mas, por algum motivo, o envio falha. Isso pode estar relacionado a problemas de configuração ou validação do modelo pela Meta.

**Veja como solucionar esse erro:**

{% hint style="success" %}
Uma alternativa é solicitar a um usuário com permissão de **super administrador** que sincronize os modelos de mensagem com a **Meta.**
{% endhint %}

Siga os passos abaixo para corrigir esse erro:

* **Acesse os Modelos de Mensagem**:
  * Localize o modelo de mensagem que você está tentando enviar no painel de "Modelos de Mensagem de Atendimento".
* **Duplique o modelo de mensagem**:
  * Crie uma cópia do modelo que apresentou o erro, mantendo o mesmo conteúdo ou realizando ajustes, se necessário.
* **Aguarde a aprovação da Meta**:
  * Após duplicar o modelo, envie-o para aprovação e aguarde até que a Meta libere o novo modelo.
* **Teste o envio novamente**:
  * Use o modelo duplicado para tentar enviar a mensagem.
* **Prevenção de problemas futuros**:
  * Se o modelo duplicado funcionar corretamente, repita o processo de duplicação para os outros modelos que possam apresentar problemas no futuro. Isso ajuda a manter a comunicação fluida e evitar interrupções.

### Erro 131047 - Mais de 24 h sem contato <a href="#id-26m6d0s9n32g" id="id-26m6d0s9n32g"></a>

<figure><img src="https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FPvg23CDIKVKngbbI1PT7%2F7.png?alt=media" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

Mais de 24 horas se passaram desde que o destinatário respondeu pela última vez ao número do remetente. Envie uma mensagem iniciada pela empresa usando um modelo de mensagem.
{% endhint %}

**Por que esse erro acontece?**

O erro 131047 ocorre porque as políticas do WhatsApp limitam o tempo em que uma empresa pode responder a uma mensagem de um cliente. Após 24 horas desde a última interação do cliente, o WhatsApp bloqueia o envio de mensagens que não sejam iniciadas pela empresa utilizando um **modelo de mensagem aprovado**.

Essa regra visa manter o ambiente de mensagens respeitoso, evitando interações não desejadas pelos usuários.

**Veja como solucionar esse erro:**

* Envie um **modelo de mensagem aprovado** para retomar o atendimento.

{% hint style="info" %}
**Observação**: Se o número do contato for editado durante uma conversa, esse erro poderá ocorrer. Por exemplo, caso o contato solicite a troca do número ou haja a necessidade de adicionar o **nono dígito**, e o usuário edite os dados enquanto a conversa está ativa, isso pode causar o erro
{% endhint %}

### Erro 131048 - Parâmetro ausente ou inválido <a href="#g8blifezkmxm" id="g8blifezkmxm"></a>

<figure><img src="https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FCupc62wayI1MT3ezUK99%2F131048.png?alt=media&#x26;token=3910a2d2-f579-400c-8803-6a2373c7dd7a" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

**Falha ao enviar a mensagem devido a um limite de envios que poder ser feitos deste número de telefone.**
{% endhint %}

**Por que esse erro acontece?**

O erro **Meta 131048** ocorre quando há um parâmetro ausente ou inválido na sua mensagem, ou quando você atingiu um **limite de envio** devido a uma baixa qualidade de mensagens, com potencial atividade de spam, ou limite de taxa de envio. Para resolver, você deve verificar se todos os dados necessários estão presentes e corretos, e reduzir a frequência de envio e o conteúdo repetitivo.

**Causas Comuns**

* **Parâmetro Ausente ou Inválido:**&#x41; mensagem que você está tentando enviar não inclui todas as informações necessárias ou contém dados incorretos.
* **Limite de Qualidade/Spam Atingido:**&#x4F; WhatsApp pode restringir o envio se sua conta tiver uma baixa classificação de qualidade devido a clientes que bloqueiam ou relatam suas mensagens como spam, ou se o número de mensagens enviadas exceder o limite diário.

**Veja como solucionar esse erro:**

* Confirme se todos os dados exigidos estão presentes e no formato correto.
* Se o erro for por excesso de mensagens, diminua a quantidade de mensagens enviadas de um determinado número.
* No WhatsApp Manager, verifique o status da qualidade da sua conta para garantir que as mensagens não estão sendo frequentemente bloqueadas ou marcadas como spam.
* Tente não enviar mensagens idênticas e repetitivas, pois isso pode ser interpretado como spam.

### Erro 132001 - Modelo não existe <a href="#g8blifezkmxm" id="g8blifezkmxm"></a>

![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FZ8CSdnzdyn2m5RJZwIRq%2F8.png?alt=media)

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

O modelo não existe no idioma especificado ou não foi aprovado.
{% endhint %}

**Por que esse erro acontece?**

O erro 13201 ocorre quando você tenta enviar um **modelo de mensagem** que não está registrado ou não é reconhecido pela API do WhatsApp. Isso pode acontecer pelos seguintes motivos:

* O modelo de mensagem foi **excluído** no Gerenciador de Negócios do WhatsApp.
* O nome do modelo foi digitado incorretamente.
* O modelo ainda está em processo de aprovação pela Meta e, portanto, não está disponível para uso.
* O modelo foi rejeitado pela Meta e, por isso, não pode ser usado.

**Veja como solucionar esse erro:**

* Uma alternativa é solicitar a um usuário com permissão de **super administrador** que sincronize os modelos de mensagem com a **Meta.**
* Crie um novo modelo de mensagem e aguarde a aprovação de Meta.
* Reenvie para aprovação caso esteja reprovado ou em análise.
* Siga as [diretrizes para modelos de mensagem](https://developers.facebook.com/docs/whatsapp/message-templates/guidelines/).

### Erro 131031 - Conta restrita ou bloqueada <a href="#ukhgiy1yhf" id="ukhgiy1yhf"></a>

![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FMyGDl4wzboGi0DSTh16Q%2F9.png?alt=media)

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

A conta do WhatsApp Business associada ao app foi restringida ou desabilitada por violar uma política da plataforma.
{% endhint %}

**Por que esse erro acontece?**

O erro 131031 ocorre quando a conta do WhatsApp Business está **restrita** ou **bloqueada** pela Meta. Isso geralmente indica que a conta violou alguma política ou regra de uso do WhatsApp Business. Entre as causas mais comuns, estão:

* **Violações das políticas da Meta**: envio de mensagens não autorizadas ou inadequadas.
* **Reclamações de usuários**: um alto número de bloqueios ou denúncias de spam por parte dos destinatários.
* **Atividades suspeitas**: uso inadequado da API, como envio de mensagens em massa ou automatizações excessivas.

**Veja como solucionar esse erro:**

*   Acesse o **portfólio empresarial** e verifique, no menu **'Página Inicial do Suporte'**, se há alguma mensagem da **Meta**.

    **Como chegar lá:**

    1. Faça login na sua conta da **Business Manager**.
    2. No menu lateral, clique em **''**![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2Fd413MqQIKs91R9URCM1X%2Fimage.png?alt=media\&token=15fae8fb-c39b-4be7-9a68-48da1d287174)", em seguida clique em **'Página Inicial do Suporte para empresas.**
    3. Verifique se há notificações ou mensagens relevantes da **Meta** relacionadas ao erro.

<figure><img src="https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2F4H7NdkZNFyRwgAZIJXLw%2FScreenshot%20(1).png?alt=media&#x26;token=36ef338a-eb18-48a7-9d23-d4703f0f7dd9" alt="" width="563"><figcaption></figcaption></figure>

* Revise as políticas de uso:
  * Certifique-se de que a conta está cumprindo as **Políticas Comerciais** e as **Políticas de Mensagens** da Meta.
  * Evite enviar mensagens não solicitadas ou que possam ser percebidas como spam pelos destinatários.
* **Responda às notificações da Meta:**
  * Se houver uma notificação ou solicitação de ação no Gerenciador de Negócios, siga as instruções fornecidas.
  * Muitas vezes, a Meta solicita informações adicionais ou ajustes nas práticas de envio para reativar a conta.
* **Corrija possíveis práticas inadequadas:**
  * Reduza o envio de mensagens para listas extensas de contatos que não interagiram recentemente com sua empresa.
  * Priorize mensagens relevantes e alinhadas às necessidades dos clientes.
  * Certifique-se de que o opt-in (consentimento do cliente para receber mensagens) esteja documentado.

### Erro 100 - Mensagem não suportada <a href="#ukhgiy1yhf" id="ukhgiy1yhf"></a>

<figure><img src="https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2FjVpqRGyM1gqZLstEsIXO%2F1.png?alt=media&#x26;token=ff130745-13d4-4d80-b054-bd072a330833" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
**A mensagem que aparece é a seguinte:**

Solicitação POST não suportada. O objeto com o ID 'messages' não existe, não pode ser carregado devido a permissões ausentes, ou não suporta esta operação. Por favor, leia a documentação da Graph API em [https://developers.facebook.com/docs/graph-api](https://developers.facebook.com/docs/graph-api).
{% endhint %}

**Por que esse erro acontece?**

* **Parâmetros Inválidos ou Ausentes:** O erro pode ser desencadeado por parâmetros incorretos ou faltantes na requisição. Por exemplo, tentar acessar um recurso com um ID inválido ou sem fornecer todos os parâmetros obrigatórios. ​[Desenvolvedores do Facebook](https://developers.facebook.com/community/threads/1221094378050282/?utm_source=chatgpt.com)
* **Recurso Inexistente ou Inacessível:** Tentar acessar um recurso que não existe ou ao qual o aplicativo não tem permissão pode resultar nesse erro. ​
* **Permissões Insuficientes:** O aplicativo pode não ter as permissões necessárias para executar a ação desejada, como enviar mensagens para determinados usuários.
* **Problemas com URLs**: Ao enviar mensagens que incluem links, URLs malformadas ou que não atendem aos requisitos da Meta podem causar o erro.

**Veja como solucionar esse erro:**

* **Verifique os Parâmetros da Requisição:** Assegure-se de que todos os parâmetros exigidos estão presentes e corretamente formatados.​
* **Confirme as Permissões do Aplicativo:** Garanta que o aplicativo possui todas as permissões necessárias para realizar a ação desejada.​ Pode ser feito o[ processo de dar permissão](https://docs.helena.app/documentacao/ajustes/conta/processo-de-dar-permissao-para-reconectar-o-numero).
* **Valide os Recursos:** Certifique-se de que os recursos que está tentando acessar existem e estão acessíveis ao aplicativo.​
* **Teste as URLs:** Se estiver enviando mensagens com links, utilize ferramentas como o[ Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/) para validar as URLs.​

### Mensagem “Mensagem não suportada pela API” O que significa e como agir - Erro 131051

Ao visualizar uma conversa na plataforma **Táime Pro**, você pode encontrar o aviso:

{% hint style="danger" %}
**"Mensagem não suportada pela API"**

Essa mensagem aparece quando o contato envia um tipo de conteúdo que **não é compatível com a API oficial da Meta** (usada na integração do WhatsApp, Instagram ou Messenger). Ou seja, a plataforma **Táime Pro não consegue exibir** ou processar esse conteúdo porque a Meta **não disponibiliza suporte** para esse formato via API.
{% endhint %}

![](https://3176979156-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F3HTAyLM7hzj1t6Nt4ii2%2Fuploads%2F2TZrfJQQuFJ9U1lkLRcL%2F0.png?alt=media)

Alguns exemplos comuns de conteúdos que podem gerar essa mensagem:

**Em quais casos essa mensagem pode aparecer?**

Ao visualizar uma conversa na plataforma **Táime Pro**, você pode encontrar o aviso:

* Esse comportamento é esperado e controlado pela Meta, e **não pode ser corrigido ou alterado pela equipe da Táime Pro**.
* Mesmo que a mensagem apareça como “não suportada”, **a conversa não é perdida** — o restante do conteúdo trocado permanece normalmente acessível.
* Esse tipo de limitação pode variar de acordo com atualizações da API oficial. A equipe da **Táime Pro** acompanha constantemente essas mudanças para garantir compatibilidade com os tipos de mensagens permitidos.

**Considerações finais**

* **Informe ao cliente** que o conteúdo enviado não é compatível com a integração oficial.
* **Peça que ele reenvie a mensagem em outro formato**, como texto, imagem ou documento padrão.
* **Não se trata de um erro da plataforma Táime Pro**, e sim de uma **limitação da API** oficial da Meta.
* Se o contato estiver tentando enviar algo com frequência que resulte nesse erro, vale instruí-lo a **evitar reações, figurinhas animadas ou formatos não convencionais**.

**O que fazer quando essa mensagem aparecer?**

* Reações a mensagens (ex: emojis de curtir ou reagir a uma mensagem no WhatsApp);
* Figurinhas animadas (stickers personalizados não compatíveis);
* Notas de voz enviadas como áudio temporário;
* Arquivos ou formatos muito recentes ainda não suportados pela API;
* Mensagens enviadas por bots ou recursos automatizados externos à Meta.
