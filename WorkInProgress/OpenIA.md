[Learn](https://learn.microsoft.com/pt-br/) [Azure](https://learn.microsoft.com/pt-br/azure/) [Serviços de IA](https://learn.microsoft.com/pt-br/azure/ai-services/) 

[Ler em inglês](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=ai-foundry-portal)

<details class="popover popover-right add-item-popover" style="box-sizing: inherit; outline-color: inherit; display: inline-block;"><summary class="button button-clear button-sm button-primary display-none display-inline-flex-tablet" data-list-type="collection" data-list-item-title="Usar seus próprios dados com o Serviço OpenAI do Azure - Azure OpenAI | Microsoft Learn" data-list-item-url="/azure/ai-services/openai/use-your-data-quickstart" data-list-source="module" data-resource-type="" data-bi-name="add-to-list" aria-describedby="popover-content" aria-expanded="false" style="box-sizing: inherit; outline-color: inherit; display: inline-flex !important; cursor: pointer; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; position: relative; background-color: rgba(0, 0, 0, 0); color: var(--theme-primary-base); text-align: center; font-weight: 600; text-decoration: none; list-style: none;"><span class="icon margin-none" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; margin: 0px !important; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-circle-addition" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="collection-status is-visually-hidden" style="box-sizing: inherit; outline-color: inherit; clip: rect(1px, 1px, 1px, 1px); clip-path: inset(50%); height: 1px; width: 1px; overflow-wrap: normal; border: 0px; margin: -1px; padding: 0px; position: absolute; overflow: hidden;">Salvar</span></summary><div class="popover-content has-z-index-one" style="box-sizing: inherit; outline-color: inherit; z-index: 1060; width: 224px; border: 1px solid var(--theme-border); background-color: var(--theme-body-background); box-shadow: 0 6.4px 14.4px 0 var(--theme-box-shadow-medium),0 1.2px 3.6px 0 var(--theme-box-shadow-light); border-radius: 0.25rem; margin-block-start: 0.5rem; padding: 1rem; position: absolute; inset-inline-end: 0px;"><ul class="list-style-none margin-inline-none" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; list-style: none !important; margin-inline: 0px !important;"><li style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; outline-style: initial; outline-width: 0px; list-style: none !important;"><button class="button button-clear button-sm button-primary" data-list-type="collection" data-list-item-title="Usar seus próprios dados com o Serviço OpenAI do Azure - Azure OpenAI | Microsoft Learn" data-list-item-url="/azure/ai-services/openai/use-your-data-quickstart" data-bi-name="add-to-collections" data-pressed="false" title="Adicionar Usar seus próprios dados com o Serviço OpenAI do Azure - Azure OpenAI | Microsoft Learn a uma coleção" style="box-sizing: inherit; outline-color: inherit; margin: 0px; font-family: inherit; font-size: 0.875rem; line-height: 1.5; overflow: visible; text-transform: none; appearance: none; color: var(--theme-primary-base); background-color: rgba(0, 0, 0, 0); cursor: pointer; user-select: none; min-height: 2.25em; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; display: inline-flex; position: relative; text-align: center; font-weight: 600; text-decoration: none;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-circle-addition" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="collection-status" style="box-sizing: inherit; outline-color: inherit;"></span></button></li><li style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; outline-style: initial; outline-width: 0px; list-style: none !important;"><button class="button button-clear button-sm button-primary" data-list-type="plan" data-list-item-title="Usar seus próprios dados com o Serviço OpenAI do Azure - Azure OpenAI | Microsoft Learn" data-list-item-url="/azure/ai-services/openai/use-your-data-quickstart" data-bi-name="add-to-plans" data-pressed="false" title="Adicionar Usar seus próprios dados com o Serviço OpenAI do Azure - Azure OpenAI | Microsoft Learn a um Plano" style="box-sizing: inherit; outline-color: inherit; margin: 0px; font-family: inherit; font-size: 0.875rem; line-height: 1.5; overflow: visible; text-transform: none; appearance: none; color: var(--theme-primary-base); background-color: rgba(0, 0, 0, 0); cursor: pointer; user-select: none; min-height: 2.25em; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; display: inline-flex; position: relative; text-align: center; font-weight: 600; text-decoration: none;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-circle-addition" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="plan-status" style="box-sizing: inherit; outline-color: inherit;"></span></button></li></ul></div></details>

<details class="popover popover-right" id="article-header-page-actions-overflow" style="box-sizing: inherit; outline-color: inherit; display: inline-block;"><summary class="justify-content-flex-start button button-clear button-sm button-primary" aria-label="Mais ações" title="Mais ações" style="box-sizing: inherit; outline-color: inherit; display: inline-flex; cursor: pointer; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; position: relative; background-color: rgba(0, 0, 0, 0); color: var(--theme-primary-base); text-align: center; font-weight: 600; text-decoration: none; list-style: none;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin: 0px;"><span class="docon docon-more-vertical" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span></summary><div class="popover-content padding-xs" style="box-sizing: inherit; outline-color: inherit; padding: 1rem; width: 224px; border: 1px solid var(--theme-border); background-color: var(--theme-body-background); box-shadow: 0 6.4px 14.4px 0 var(--theme-box-shadow-medium),0 1.2px 3.6px 0 var(--theme-box-shadow-light); z-index: 1060; border-radius: 0.25rem; margin-block-start: 0.5rem; position: absolute; inset-inline-end: 0px;"><div aria-hidden="true" class="margin-none" data-page-action-item="overflow-all" style="box-sizing: inherit; outline-color: inherit; margin: 0px !important;"></div><h4 class="font-size-sm padding-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; font-size: 0.875rem !important; font-weight: 600; padding-inline-start: 0.5rem !important;"></h4><a class="button button-clear button-sm button-block has-inner-focus text-decoration-none justify-content-flex-start share-facebook" data-bi-name="facebook" data-page-action-item="overflow-all" href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Flearn.microsoft.com%2Fpt-br%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Cjavascript-keyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Dfacebook%26sharingId%3D4FABF1D0ABA789BB" style="box-sizing: inherit; outline-color: inherit; color: currentcolor; cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; display: flex; position: relative; text-align: center; font-weight: 600; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-facebook-share font-size-md color-primary" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-primary-base) !important; font-size: inherit; font-family: docons; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></a><a class="button button-clear button-sm has-inner-focus button-block text-decoration-none justify-content-flex-start share-twitter" data-bi-name="twitter" data-page-action-item="overflow-all" href="https://twitter.com/intent/tweet?original_referer=https%3A%2F%2Flearn.microsoft.com%2Fpt-br%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Cjavascript-keyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Dtwitter%26sharingId%3D4FABF1D0ABA789BB&amp;text=Hoje%20eu%20completei%20%22Usar%20seus%20pr%C3%B3prios%20dados%20com%20o%20Servi%C3%A7o%20OpenAI%20do%20Azure%20-%20Azure%20OpenAI%20%7C%20Microsoft%20Learn%22!%20Tenho%20muito%20orgulho%20desta%20conquista%20e%20espero%20que%20isso%20inspire%20voc%C3%AA%20a%20come%C3%A7ar%20seu%20pr%C3%B3prio%20percurso%20do%20%40MicrosoftLearn.&amp;tw_p=tweetbutton&amp;url=https%3A%2F%2Flearn.microsoft.com%2Fpt-br%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Cjavascript-keyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Dtwitter%26sharingId%3D4FABF1D0ABA789BB" style="box-sizing: inherit; outline-color: inherit; color: currentcolor; cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; display: flex; position: relative; text-align: center; font-weight: 600; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-xlogo-share font-size-xxs" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></a><a class="button button-clear button-sm has-inner-focus button-block text-decoration-none justify-content-flex-start share-linkedin" data-bi-name="linkedin" data-page-action-item="overflow-all" href="https://www.linkedin.com/feed/?shareActive=true&amp;text=Hoje%20eu%20completei%20%22Usar%20seus%20pr%C3%B3prios%20dados%20com%20o%20Servi%C3%A7o%20OpenAI%20do%20Azure%20-%20Azure%20OpenAI%20%7C%20Microsoft%20Learn%22!%20Tenho%20muito%20orgulho%20desta%20conquista%20e%20espero%20que%20isso%20inspire%20voc%C3%AA%20a%20come%C3%A7ar%20seu%20pr%C3%B3prio%20percurso%20do%20%40MicrosoftLearn.%0A%0D%0Ahttps%3A%2F%2Flearn.microsoft.com%2Fpt-br%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Cjavascript-keyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Dlinkedin%26sharingId%3D4FABF1D0ABA789BB" style="box-sizing: inherit; outline-color: inherit; color: currentcolor; cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; display: flex; position: relative; text-align: center; font-weight: 600; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-linked-in-logo font-size-sm color-primary" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-primary-base) !important; font-size: inherit; font-family: docons; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></a><a class="button button-clear button-sm button-block has-inner-focus text-decoration-none justify-content-flex-start margin-bottom-xxs share-email" data-bi-name="email" data-page-action-item="overflow-all" href="mailto:?subject=%5BArtigo%20compartilhado%5D%20Usar%20seus%20pr%C3%B3prios%20dados%20com%20o%20Servi%C3%A7o%20OpenAI%20do%20Azure%20-%20Azure%20OpenAI%20%7C%20Microsoft%20Learn&amp;body=Hoje%20eu%20completei%20%22Usar%20seus%20pr%C3%B3prios%20dados%20com%20o%20Servi%C3%A7o%20OpenAI%20do%20Azure%20-%20Azure%20OpenAI%20%7C%20Microsoft%20Learn%22!%20Tenho%20muito%20orgulho%20desta%20conquista%20e%20espero%20que%20isso%20inspire%20voc%C3%AA%20a%20come%C3%A7ar%20seu%20pr%C3%B3prio%20percurso%20do%20%40MicrosoftLearn.%0A%0D%0Ahttps%3A%2F%2Flearn.microsoft.com%2Fpt-br%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Cjavascript-keyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Demail%26sharingId%3D4FABF1D0ABA789BB" style="box-sizing: inherit; outline-color: inherit; color: currentcolor; cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; display: flex; position: relative; margin-block-end: 0.5rem !important; text-align: center; font-weight: 600; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-mail-message font-size-sm color-primary" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-primary-base) !important; font-size: inherit; font-family: docons; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></a><hr style="box-sizing: inherit; outline-color: inherit; height: 0px; overflow: visible; margin: 0px; padding: 0px; border-style: solid; border-width: 1px 0px 0px; border-color: var(--theme-border);"><button class="button button-block button-clear button-sm justify-content-flex-start has-inner-focus margin-top-xxs" title="Imprimir" type="button" aria-label="Imprimir" data-bi-name="print" data-page-action-item="overflow-all" data-popover-close="" data-print-page="" data-check-hidden="true" style="box-sizing: inherit; outline-color: inherit; margin: 0px; font-family: inherit; font-size: 0.875rem; line-height: 1.5; overflow: visible; text-transform: none; appearance: button; color: currentcolor; background-color: rgba(0, 0, 0, 0); cursor: pointer; user-select: none; min-height: 2.25em; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; display: flex; position: relative; margin-block-start: 0.5rem !important; text-align: center; font-weight: 600; text-decoration: none; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-print font-size-sm color-primary" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-primary-base) !important; font-size: inherit; font-family: docons; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></button></div></details>

# Início Rápido: converse com modelos do OpenAI do Azure usando seus próprios dados

- Artigo
- 09/01/2025
- 17 colaboradores

Comentários

Escolha o método de uso de sua preferência

PortalC#GoJavaScriptPythonRESTPowerShellSpringTypeScript

Neste artigo[Pré-requisitos](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#prerequisites-5)[Adicione seus dados usando o portal da Fábrica de IA do Azure](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#add-your-data-using-azure-ai-foundry-portal)[Recuperar as informações do recurso](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#retrieve-resource-information)[Criar um ambiente de Python](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#create-a-python-environment)Mostrar mais 3

Neste início rápido, você pode usar seus próprios dados com os modelos do OpenAI do Azure. O uso dos modelos do OpenAI do Azure em seus dados pode lhe fornecer uma poderosa plataforma de IA de conversação que permite uma comunicação mais rápida e precisa.



## Pré-requisitos

Use os seguintes recursos:

- [OpenAI do Azure](https://portal.azure.com/#create/Microsoft.CognitiveServicesOpenAI)

- [Armazenamento de Blobs do Azure](https://portal.azure.com/#create/Microsoft.StorageAccount-ARM)

- [Azure AI Search](https://portal.azure.com/#create/Microsoft.Search)

- Um

   

  recurso do OpenAI do Azure

   

  implantado em uma

   

  região com suporte e com um modelo com suporte

  .

  - Verifique se você recebeu, pelo menos, a [função Colaborador de Serviços Cognitivos](https://learn.microsoft.com/pt-br/azure/ai-services/openai/how-to/role-based-access-control#cognitive-services-contributor) no recurso do OpenAI do Azure.

- Baixe os dados de exemplo do [GitHub](https://github.com/Azure-Samples/cognitive-services-sample-data-files/blob/master/openai/contoso_benefits_document_example.pdf) se você não tiver seus próprios dados.

[Referência](https://platform.openai.com/docs/api-reference?lang=python) | [Código-fonte](https://github.com/openai/openai-python) | [Pacote (PyPi)](https://pypi.org/project/openai/) | [Amostras](https://github.com/openai/openai-cookbook/)

Esses links referenciam a API do OpenAI para Python. Não há um SDK do OpenAI para Python específico para o Azure. [Saiba como alternar entre os serviços do OpenAI e os serviços do OpenAI do Azure](https://learn.microsoft.com/pt-br/azure/ai-services/openai/how-to/switching-endpoints).



## Adicione seus dados usando o portal da Fábrica de IA do Azure

 Dica

Você pode [usar o Azure Developer CLI](https://learn.microsoft.com/pt-br/azure/ai-services/openai/how-to/azure-developer-cli) para criar programaticamente os recursos necessários para o OpenAI do Azure em seus dados

Navegue até o [portal da Fábrica de IA do Azure](https://ai.azure.com/) e entre com credenciais que tenham acesso ao seu recurso OpenAI do Azure.

1. Você pode [criar um projeto do Azure AI Foundry](https://learn.microsoft.com/pt-br/azure/ai-studio/how-to/create-projects) clicando em **Criar projeto** ou continuar diretamente clicando no botão no bloco **Focado no Serviço OpenAI do Azure**.

   [![Uma captura de tela da página de aterrissagem do portal do Azure AI Foundry.](https://learn.microsoft.com/pt-br/azure/ai-services/openai/media/use-your-data/ai-studio-homepage.png)](https://learn.microsoft.com/pt-br/azure/ai-services/openai/media/use-your-data/ai-studio-homepage.png#lightbox)

2. Selecione **Chat** em **Playgrounds** no menu de navegação à esquerda e selecione a implantação de modelo.

3. No **Playground de chat**, selecione **Adicionar seus dados** e, em seguida, **Adicionar uma fonte de dados**

   [![Captura de tela do playground de chat no Azure AI Foundry.](https://learn.microsoft.com/pt-br/azure/ai-services/openai/media/use-your-data/chat-playground.png)](https://learn.microsoft.com/pt-br/azure/ai-services/openai/media/use-your-data/chat-playground.png#lightbox)

4. No painel que aparece, selecione **Carregar arquivos** (versão prévia) em **Selecionar fonte de dados** . O OpenAI do Azure precisa de um recurso de armazenamento e de um recurso de pesquisa para acessar e indexar seus dados.

    Dica

   - Confira o seguinte recurso para obter mais informações:
     - [Opções de fonte de dados](https://learn.microsoft.com/pt-br/azure/ai-services/openai/concepts/use-your-data#supported-data-sources)
     - [tipos de arquivo e formatos com suporte](https://learn.microsoft.com/pt-br/azure/ai-services/openai/concepts/use-your-data#data-formats-and-file-types)
   - Para documentos e conjuntos de dados com texto longo, recomendamos usar o [script de preparação de dados](https://go.microsoft.com/fwlink/?linkid=2244395) disponível.

   1. Para que o OpenAI do Azure acesse sua conta de armazenamento, você precisará ativar o [Compartilhamento de recursos entre origens (CORS)](https://go.microsoft.com/fwlink/?linkid=2237228). Se o CORS ainda não estiver ativado para o recurso de Armazenamento de Blobs do Azure, selecione **Ativar o CORS**.
   2. Selecione seu recurso de Pesquisa de IA do Azure e selecione a confirmação de que a sua conexão incorrerá em uso em sua conta. Em seguida, selecione **Avançar**.

   [![Uma captura de tela mostrando opções para selecionar uma fonte de dados no portal da Fábrica de IA do Azure.](https://learn.microsoft.com/pt-br/azure/ai-services/openai/media/quickstarts/add-your-data-source.png)](https://learn.microsoft.com/pt-br/azure/ai-services/openai/media/quickstarts/add-your-data-source.png#lightbox)

5. No painel **Carregar arquivos**, selecione **Procurar um arquivo** e selecione os arquivos baixados na seção [pré-requisitos](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#prerequisites) ou seus próprios dados. Em seguida, selecione **Carregar arquivos**. Em seguida, selecione **Avançar**.

6. No painel **Gerenciamento de dados**, você pode escolher se deseja habilitar a [pesquisa semântica ou a busca em vetores](https://learn.microsoft.com/pt-br/azure/ai-services/openai/concepts/use-your-data#search-types) para o índice.

    Importante

   - A [pesquisa semântica](https://learn.microsoft.com/pt-br/azure/search/semantic-search-overview#availability-and-pricing) e a [busca em vetores](https://azure.microsoft.com/pricing/details/cognitive-services/openai-service/) estão sujeitas a preços adicionais. Você precisa escolher o **SKU Básico ou superior** para habilitar a pesquisa semântica ou a busca em vetores. Confira [diferença dos tipos de preço](https://learn.microsoft.com/pt-br/azure/search/search-sku-tier) e os [limites de serviço](https://learn.microsoft.com/pt-br/azure/search/search-limits-quotas-capacity) para mais informações.
   - Para ajudar a melhorar a qualidade da recuperação de informações e da resposta do modelo, recomendamos habilitar a [pesquisa semântica](https://learn.microsoft.com/pt-br/azure/search/semantic-search-overview) para os idiomas de fonte de dados a seguir: inglês, francês, espanhol, português, italiano, alemão, chinês (Zh), japonês, coreano, russo e árabe.

7. Reveja os detalhes inseridos e selecione **Salvar e fechar**. Agora é possível conversar com o modelo e ele usará as informações dos seus dados para construir a resposta.



## Recuperar as informações do recurso

Você precisa recuperar as seguintes informações para autenticar seu aplicativo com seu recurso OpenAI do Azure. Esse início rápido pressupõe que você tenha carregado seus dados em uma conta de armazenamento de blobs do Azure e tenha criado um índice da Pesquisa de IA do Azure. Consulte [Adicionar seus dados usando o portal da Fábrica de IA do Azure](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?pivots=programming-language-studio).

- [Microsoft Entra ID](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_1_keyless)
- [Chave de API](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_1_api-key)

Expandir a tabela

| Nome da variável             | Valor                                                        |
| :--------------------------- | :----------------------------------------------------------- |
| `AZURE_OPENAI_ENDPOINT`      | Esse valor pode ser encontrado na seção **Chaves e Ponto de Extremidade** ao examinar seu recurso do OpenAI do Azure no portal do Azure. Um ponto de extremidade de exemplo é: `https://my-resoruce.openai.azure.com`. |
| `AZURE_OPENAI_DEPLOYMENT_ID` | Esse valor corresponde ao nome personalizado escolhido para sua implantação ao implantar um modelo. Esse valor pode ser encontrado em **Gerenciamento de Recursos**>**Implantações** no portal do Azure. |
| `AZURE_AI_SEARCH_ENDPOINT`   | Esse valor pode ser encontrado na seção **Visão Geral** ao examinar o seu recurso de Pesquisa de IA do Azure no portal do Azure. |
| `AZURE_AI_SEARCH_INDEX`      | Esse valor corresponde ao nome do índice que você criou para armazenar seus dados. Você pode encontrá-lo na seção **Visão geral** ao examinar seu recurso de Pesquisa de IA do Azure no portal do Azure. |

Saiba mais sobre [autenticação sem chave](https://learn.microsoft.com/pt-br/azure/ai-services/authentication) e [configuração de variáveis de ambiente](https://learn.microsoft.com/pt-br/azure/ai-services/cognitive-services-environment-variables).



## Criar um ambiente de Python

1. Crie uma pasta chamada *openai-python* para seu projeto e um novo arquivo de código Python chamado *main.py*. Mude para esse diretório:

Prompt de comando do Windows

```cmd
mkdir openai-python
cd openai-python
```

1. Instale as seguintes bibliotecas do Python:

- [OpenAI Python 1.x](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_1_python-new)
- [OpenAI Python 0.28.1](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_1_python)

Console

```console
pip install openai
pip install python-dotenv
```



## Criar o aplicativo do Python

1. No diretório do projeto, abra o arquivo *main.py* e adicione o seguinte código:

- [OpenAI Python 1.x](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_2_python-new)
- [OpenAI Python 0.28.1](https://learn.microsoft.com/pt-br/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_2_python)

Python

```python
import os
import openai
import dotenv

dotenv.load_dotenv()

endpoint = os.environ.get("AZURE_OPENAI_ENDPOINT")
api_key = os.environ.get("AZURE_OPENAI_API_KEY")
deployment = os.environ.get("AZURE_OPENAI_DEPLOYMENT_ID")

client = openai.AzureOpenAI(
    azure_endpoint=endpoint,
    api_key=api_key,
    api_version="2024-10-21",
)

completion = client.chat.completions.create(
    model=deployment,
    messages=[
        {
            "role": "user",
            "content": "What are my available health plans?",
        },
    ],
    extra_body={
        "data_sources":[
            {
                "type": "azure_search",
                "parameters": {
                    "endpoint": os.environ["AZURE_AI_SEARCH_ENDPOINT"],
                    "index_name": os.environ["AZURE_AI_SEARCH_INDEX"],
                    "authentication": {
                        "type": "api_key",
                        "key": os.environ["AZURE_AI_SEARCH_API_KEY"],
                    }
                }
            }
        ],
    }
)

print(f"{completion.choices[0].message.role}: {completion.choices[0].message.content}")
```

 Importante

Para produção, use uma maneira segura de armazenar e acessar suas credenciais, como o [Azure Key Vault](https://learn.microsoft.com/pt-br/azure/key-vault/general/overview). Para obter mais informações sobre segurança de credenciais, consulte o artigo [segurança](https://learn.microsoft.com/pt-br/azure/ai-services/security-features) dos serviços de IA do Azure.

1. Execute o comando a seguir:

Prompt de comando do Windows

```cmd
python main.py
```

O aplicativo imprime a resposta em um formato JSON adequado para uso em vários cenários. Ele inclui respostas para sua consulta e citações dos arquivos carregados.



## Limpar os recursos

Se você quiser limpar e remover um recurso do OpenAI do Azure ou da Pesquisa de IA do Azure, poderá excluir o recurso ou o grupo de recursos. Excluir o grupo de recursos também exclui todos os recursos associados a ele.

- [Recursos dos serviços de IA do Azure](https://learn.microsoft.com/pt-br/azure/ai-services/multi-service-resource?pivots=azportal#clean-up-resources)
- [Recursos da Pesquisa de IA do Azure](https://learn.microsoft.com/pt-br/azure/search/search-get-started-portal#clean-up-resources)
- [Recursos do serviço de aplicativos do Azure](https://learn.microsoft.com/pt-br/azure/app-service/quickstart-dotnetcore?pivots=development-environment-vs#clean-up-resources)



## Próximas etapas

- Saiba mais sobre o [uso dos seus dados no Serviço OpenAI do Azure](https://learn.microsoft.com/pt-br/azure/ai-services/openai/concepts/use-your-data)
- [Exemplo de código do aplicativo de chat no GitHub](https://go.microsoft.com/fwlink/?linkid=2244395).