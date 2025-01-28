- [Skip to main content](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#main)

  

  [Learn](https://learn.microsoft.com/en-us/)

  DiscoverProduct documentationDevelopment languagesTopics

  <details data-bi-name="site-header-user" class="popover popover-right auth-status-determined authenticated " style="box-sizing: inherit; outline-color: inherit; display: inline-block;"><summary data-bi-name="site-header-user-avatar" aria-label="Your Account" data-test-id="site-header-user" style="box-sizing: inherit; outline-color: inherit; display: list-item; cursor: pointer; list-style: none;"><div class="persona " style="box-sizing: inherit; outline-color: inherit; gap: 0.5rem; font-size: 0.875rem; line-height: 1.3; display: flex; position: relative;"><figure class="persona-avatar" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; width: 2.6666em; height: 2.6666em; background-color: var(--theme-alternate-background-medium); color: var(--theme-text-invert); border-radius: 290486px; flex-shrink: 0;"><img alt="" data-profile-property="avatarThumbnailUrl" src="data:image/svg+xml, %3Csvg xmlns='http://www.w3.org/2000/svg' height='64' class='font-weight-bold' style='font: 600 30.11764705882353px &quot;SegoeUI&quot;, Arial' width='64'%3E%3Ccircle fill='hsl(224.00000000000003, 82%, 31%)' cx='32' cy='32' r='32' /%3E%3Ctext x='50%25' y='55%25' dominant-baseline='middle' text-anchor='middle' fill='%23FFF' %3EVR%3C/text%3E%3C/svg%3E" style="box-sizing: inherit; outline-color: inherit; border-style: none; height: auto; max-width: 100%; width: 37.3281px; aspect-ratio: 1 / 1; border-radius: 290486px;"></figure></div></summary><div class="popover-content width-auto" data-bi-name="site-header-user-menu" style="box-sizing: inherit; outline-color: inherit; width: 224px; border: 1px solid var(--theme-border); background-color: var(--theme-body-background); box-shadow: 0 6.4px 14.4px 0 var(--theme-box-shadow-medium),0 1.2px 3.6px 0 var(--theme-box-shadow-light); z-index: 1060; border-radius: 0.25rem; margin-block-start: 0.5rem; padding: 1rem; position: absolute; inset-inline-end: 0px;"><div class="persona " style="box-sizing: inherit; outline-color: inherit; gap: 0.5rem; font-size: 0.875rem; line-height: 1.3; display: flex; position: relative;"><figure class="persona-avatar" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; width: 2.6666em; height: 2.6666em; background-color: var(--theme-alternate-background-medium); color: var(--theme-text-invert); border-radius: 290486px; flex-shrink: 0;"><img alt="" data-profile-property="avatarUrl" aria-labelledby="ms--user-display-name" src="data:image/svg+xml, %3Csvg xmlns='http://www.w3.org/2000/svg' height='64' class='font-weight-bold' style='font: 600 30.11764705882353px &quot;SegoeUI&quot;, Arial' width='64'%3E%3Ccircle fill='hsl(224.00000000000003, 82%, 31%)' cx='32' cy='32' r='32' /%3E%3Ctext x='50%25' y='55%25' dominant-baseline='middle' text-anchor='middle' fill='%23FFF' %3EVR%3C/text%3E%3C/svg%3E" style="box-sizing: inherit; outline-color: inherit; border-style: none; height: auto; max-width: 100%; width: 37.3281px; aspect-ratio: 1 / 1; border-radius: 290486px;"></figure><div class="persona-details" data-test-id="persona-detail" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-text-subtle); align-self: center;"><p class="persona-name" data-profile-property="displayName" id="ms--user-display-name" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; color: var(--theme-text); font-size: 1.3333em; font-weight: 600;"></p><p data-profile-property="upn" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px;"></p></div></div><ul class="padding-block-xs" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; list-style: none; padding-block: 1rem !important;"><li class="padding-bottom-xs" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; outline-style: initial; outline-width: 0px; padding-block-end: 1rem !important;"><a data-profile-property="profileUrl" class="font-size-sm" data-bi-name="site-header-user-profile" href="https://learn.microsoft.com/en-us/users/me/activity/" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-hyperlink); cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; font-size: 0.875rem !important;"></a></li><li style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; outline-style: initial; outline-width: 0px;"><a data-profile-property="settingsUrl" class="font-size-sm" data-bi-name="site-header-user-settings" href="https://learn.microsoft.com/en-us/users/me/settings/" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-hyperlink); cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; font-size: 0.875rem !important;"></a></li></ul><div class="border-top padding-top-xs" style="box-sizing: inherit; outline-color: inherit; border-block-start: 1px solid var(--theme-border) !important; padding-block-start: 1rem !important;"><a class="docs-sign-out font-size-sm" href="https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&amp;pivots=programming-language-python#" data-bi-name="site-header-sign-out" data-test-id="site-header-user-sign-out" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-hyperlink); cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; font-size: 0.875rem !important;"></a></div></div></details>

  [Azure](https://learn.microsoft.com/en-us/azure/)

  ProductsArchitectureDevelopLearn Azure[Troubleshooting](https://learn.microsoft.com/en-us/troubleshoot/azure/)Resources

  

  [Portal](https://portal.azure.com/)[Free account](https://azure.microsoft.com/free/)

  Search

  - [Azure OpenAI Service Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
  - Overview
    - [What is Azure OpenAI?](https://learn.microsoft.com/en-us/azure/ai-services/openai/overview)
    - [Quotas and limits](https://learn.microsoft.com/en-us/azure/ai-services/openai/quotas-limits)
    - [Deployment types](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/deployment-types)
    - [Models](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models)
    - [Model retirements](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/model-retirements)
    - [Pricing](https://azure.microsoft.com/pricing/details/cognitive-services/openai-service/)
    - [What's new](https://learn.microsoft.com/en-us/azure/ai-services/openai/whats-new)
    - [Programming languages/SDKs](https://learn.microsoft.com/en-us/azure/ai-services/openai/supported-languages)
    - [Azure OpenAI FAQ](https://learn.microsoft.com/en-us/azure/ai-services/openai/faq)
    - [Azure OpenAI in Azure Government](https://learn.microsoft.com/en-us/azure/ai-services/openai/azure-government)
  - Quickstarts
    - [Assistants (preview)](https://learn.microsoft.com/en-us/azure/ai-services/openai/assistants-quickstart)
    - [Audio generation](https://learn.microsoft.com/en-us/azure/ai-services/openai/audio-completions-quickstart)
    - [Chat](https://learn.microsoft.com/en-us/azure/ai-services/openai/chatgpt-quickstart)
    - [Vision-enabled chats](https://learn.microsoft.com/en-us/azure/ai-services/openai/gpt-v-quickstart)
    - [DALL-E](https://learn.microsoft.com/en-us/azure/ai-services/openai/dall-e-quickstart)
    - [Use your data](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart)
    - [Realtime API for speech and audio (preview)](https://learn.microsoft.com/en-us/azure/ai-services/openai/realtime-audio-quickstart)
    - [Whisper model](https://learn.microsoft.com/en-us/azure/ai-services/openai/whisper-quickstart)
    - [Text to speech (preview)](https://learn.microsoft.com/en-us/azure/ai-services/openai/text-to-speech-quickstart)
    - [Completions (legacy)](https://learn.microsoft.com/en-us/azure/ai-services/openai/quickstart)
  - Concepts
  - How-to
  - Tutorials
  - Security & Governance
  - Responsible AI
  - Reference
  - Resources

  Download PDF

  [Learn](https://learn.microsoft.com/en-us/) [Azure](https://learn.microsoft.com/en-us/azure/) [AI Services](https://learn.microsoft.com/en-us/azure/ai-services/) 

  <details class="popover popover-right add-item-popover" style="box-sizing: inherit; outline-color: inherit; display: inline-block;"><summary class="button button-clear button-sm button-primary display-none display-inline-flex-tablet" data-list-type="collection" data-list-item-title="Use your own data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn" data-list-item-url="/azure/ai-services/openai/use-your-data-quickstart" data-list-source="module" data-resource-type="" data-bi-name="add-to-list" aria-describedby="popover-content" aria-expanded="false" style="box-sizing: inherit; outline-color: inherit; display: inline-flex !important; cursor: pointer; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; position: relative; background-color: rgba(0, 0, 0, 0); color: var(--theme-primary-base); text-align: center; font-weight: 600; text-decoration: none; list-style: none;"><span class="icon margin-none" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; margin: 0px !important; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-circle-addition" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="collection-status is-visually-hidden" style="box-sizing: inherit; outline-color: inherit; clip: rect(1px, 1px, 1px, 1px); clip-path: inset(50%); height: 1px; width: 1px; overflow-wrap: normal; border: 0px; margin: -1px; padding: 0px; position: absolute; overflow: hidden;">Save</span></summary><div class="popover-content has-z-index-one" style="box-sizing: inherit; outline-color: inherit; z-index: 1060; width: 224px; border: 1px solid var(--theme-border); background-color: var(--theme-body-background); box-shadow: 0 6.4px 14.4px 0 var(--theme-box-shadow-medium),0 1.2px 3.6px 0 var(--theme-box-shadow-light); border-radius: 0.25rem; margin-block-start: 0.5rem; padding: 1rem; position: absolute; inset-inline-end: 0px;"><ul class="list-style-none margin-inline-none" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; list-style: none !important; margin-inline: 0px !important;"><li style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; outline-style: initial; outline-width: 0px; list-style: none !important;"><button class="button button-clear button-sm button-primary" data-list-type="collection" data-list-item-title="Use your own data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn" data-list-item-url="/azure/ai-services/openai/use-your-data-quickstart" data-bi-name="add-to-collections" data-pressed="false" title="Add Use your own data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn to a collection" style="box-sizing: inherit; outline-color: inherit; margin: 0px; font-family: inherit; font-size: 0.875rem; line-height: 1.5; overflow: visible; text-transform: none; appearance: none; color: var(--theme-primary-base); background-color: rgba(0, 0, 0, 0); cursor: pointer; user-select: none; min-height: 2.25em; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; display: inline-flex; position: relative; text-align: center; font-weight: 600; text-decoration: none;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-circle-addition" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="collection-status" style="box-sizing: inherit; outline-color: inherit;"></span></button></li><li style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; outline-style: initial; outline-width: 0px; list-style: none !important;"><button class="button button-clear button-sm button-primary" data-list-type="plan" data-list-item-title="Use your own data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn" data-list-item-url="/azure/ai-services/openai/use-your-data-quickstart" data-bi-name="add-to-plans" data-pressed="false" title="Add Use your own data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn to a plan" style="box-sizing: inherit; outline-color: inherit; margin: 0px; font-family: inherit; font-size: 0.875rem; line-height: 1.5; overflow: visible; text-transform: none; appearance: none; color: var(--theme-primary-base); background-color: rgba(0, 0, 0, 0); cursor: pointer; user-select: none; min-height: 2.25em; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; display: inline-flex; position: relative; text-align: center; font-weight: 600; text-decoration: none;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-circle-addition" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="plan-status" style="box-sizing: inherit; outline-color: inherit;"></span></button></li></ul></div></details>

  

  <details class="popover popover-right" id="article-header-page-actions-overflow" style="box-sizing: inherit; outline-color: inherit; display: inline-block;"><summary class="justify-content-flex-start button button-clear button-sm button-primary" aria-label="More actions" title="More actions" style="box-sizing: inherit; outline-color: inherit; display: inline-flex; cursor: pointer; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; position: relative; background-color: rgba(0, 0, 0, 0); color: var(--theme-primary-base); text-align: center; font-weight: 600; text-decoration: none; list-style: none;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin: 0px;"><span class="docon docon-more-vertical" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span></summary><div class="popover-content padding-xs" style="box-sizing: inherit; outline-color: inherit; padding: 1rem; width: 224px; border: 1px solid var(--theme-border); background-color: var(--theme-body-background); box-shadow: 0 6.4px 14.4px 0 var(--theme-box-shadow-medium),0 1.2px 3.6px 0 var(--theme-box-shadow-light); z-index: 1060; border-radius: 0.25rem; margin-block-start: 0.5rem; position: absolute; inset-inline-end: 0px;"><div aria-hidden="true" class="margin-none" data-page-action-item="overflow-all" style="box-sizing: inherit; outline-color: inherit; margin: 0px !important;"></div><h4 class="font-size-sm padding-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin: 0px; padding: 0px; font-size: 0.875rem !important; font-weight: 600; padding-inline-start: 0.5rem !important;"></h4><a class="button button-clear button-sm button-block has-inner-focus text-decoration-none justify-content-flex-start share-facebook" data-bi-name="facebook" data-page-action-item="overflow-all" href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Flearn.microsoft.com%2Fen-us%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Dfacebook%26sharingId%3D4FABF1D0ABA789BB" style="box-sizing: inherit; outline-color: inherit; color: currentcolor; cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; display: flex; position: relative; text-align: center; font-weight: 600; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-facebook-share font-size-md color-primary" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-primary-base) !important; font-size: inherit; font-family: docons; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></a><a class="button button-clear button-sm has-inner-focus button-block text-decoration-none justify-content-flex-start share-twitter" data-bi-name="twitter" data-page-action-item="overflow-all" href="https://twitter.com/intent/tweet?original_referer=https%3A%2F%2Flearn.microsoft.com%2Fen-us%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Dtwitter%26sharingId%3D4FABF1D0ABA789BB&amp;text=Today%20I%20completed%20%22Use%20your%20own%20data%20with%20Azure%20OpenAI%20Service%20-%20Azure%20OpenAI%20%7C%20Microsoft%20Learn%22!%20I%27m%20so%20proud%20to%20be%20celebrating%20this%20achievement%20and%20hope%20this%20inspires%20you%20to%20start%20your%20own%20%40MicrosoftLearn%20journey!&amp;tw_p=tweetbutton&amp;url=https%3A%2F%2Flearn.microsoft.com%2Fen-us%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Dtwitter%26sharingId%3D4FABF1D0ABA789BB" style="box-sizing: inherit; outline-color: inherit; color: currentcolor; cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; display: flex; position: relative; text-align: center; font-weight: 600; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-xlogo-share font-size-xxs" style="box-sizing: inherit; outline-color: inherit; font-family: docons; font-size: inherit; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></a><a class="button button-clear button-sm has-inner-focus button-block text-decoration-none justify-content-flex-start share-linkedin" data-bi-name="linkedin" data-page-action-item="overflow-all" href="https://www.linkedin.com/feed/?shareActive=true&amp;text=Today%20I%20completed%20%22Use%20your%20own%20data%20with%20Azure%20OpenAI%20Service%20-%20Azure%20OpenAI%20%7C%20Microsoft%20Learn%22!%20I%27m%20so%20proud%20to%20be%20celebrating%20this%20achievement%20and%20hope%20this%20inspires%20you%20to%20start%20your%20own%20%40MicrosoftLearn%20journey!%0A%0D%0Ahttps%3A%2F%2Flearn.microsoft.com%2Fen-us%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Dlinkedin%26sharingId%3D4FABF1D0ABA789BB" style="box-sizing: inherit; outline-color: inherit; color: currentcolor; cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; display: flex; position: relative; text-align: center; font-weight: 600; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-linked-in-logo font-size-sm color-primary" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-primary-base) !important; font-size: inherit; font-family: docons; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></a><a class="button button-clear button-sm button-block has-inner-focus text-decoration-none justify-content-flex-start margin-bottom-xxs share-email" data-bi-name="email" data-page-action-item="overflow-all" href="mailto:?subject=%5BShared%20Article%5D%20Use%20your%20own%20data%20with%20Azure%20OpenAI%20Service%20-%20Azure%20OpenAI%20%7C%20Microsoft%20Learn&amp;body=Today%20I%20completed%20%22Use%20your%20own%20data%20with%20Azure%20OpenAI%20Service%20-%20Azure%20OpenAI%20%7C%20Microsoft%20Learn%22!%20I%27m%20so%20proud%20to%20be%20celebrating%20this%20achievement%20and%20hope%20this%20inspires%20you%20to%20start%20your%20own%20%40MicrosoftLearn%20journey!%0A%0D%0Ahttps%3A%2F%2Flearn.microsoft.com%2Fen-us%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%252Ctypescript-keyless%252Cpython-new%26pivots%3Dai-foundry-portal%26WT.mc_id%3Demail%26sharingId%3D4FABF1D0ABA789BB" style="box-sizing: inherit; outline-color: inherit; color: currentcolor; cursor: pointer; overflow-wrap: break-word; text-decoration: none; background-color: rgba(0, 0, 0, 0); outline-style: initial; outline-width: 0px; user-select: none; min-height: 2.25em; appearance: none; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; font-size: 0.875rem; line-height: 1.5; display: flex; position: relative; margin-block-end: 0.5rem !important; text-align: center; font-weight: 600; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-mail-message font-size-sm color-primary" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-primary-base) !important; font-size: inherit; font-family: docons; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></a><hr style="box-sizing: inherit; outline-color: inherit; height: 0px; overflow: visible; margin: 0px; padding: 0px; border-style: solid; border-width: 1px 0px 0px; border-color: var(--theme-border);"><button class="button button-block button-clear button-sm justify-content-flex-start has-inner-focus margin-top-xxs" title="Print" type="button" aria-label="Print" data-bi-name="print" data-page-action-item="overflow-all" data-popover-close="" data-print-page="" data-check-hidden="true" style="box-sizing: inherit; outline-color: inherit; margin: 0px; font-family: inherit; font-size: 0.875rem; line-height: 1.5; overflow: visible; text-transform: none; appearance: button; color: currentcolor; background-color: rgba(0, 0, 0, 0); cursor: pointer; user-select: none; min-height: 2.25em; box-shadow: none; vertical-align: top; border: 1px solid rgba(0, 0, 0, 0); border-radius: 0.25rem; justify-content: center; align-items: center; padding-block: calc(0.375em - 1px); padding-inline: 0.75em; display: flex; position: relative; margin-block-start: 0.5rem !important; text-align: center; font-weight: 600; text-decoration: none; width: 190px;"><span class="icon" aria-hidden="true" style="box-sizing: inherit; outline-color: inherit; justify-content: center; align-items: center; display: inline-flex; width: 1em; height: 1em; font-size: 0.875em; margin-inline-end: 0.375em;"><span class="docon docon-print font-size-sm color-primary" style="box-sizing: inherit; outline-color: inherit; color: var(--theme-primary-base) !important; font-size: inherit; font-family: docons; speak: none; font-variant: normal; text-transform: none; text-align: center; direction: ltr; -webkit-font-smoothing: antialiased; font-style: normal; font-weight: 400; line-height: 16px; display: inline-block;"></span></span><span class="margin-left-xxs" style="box-sizing: inherit; outline-color: inherit; margin-inline-start: 0.5rem !important;"></span></button></div></details>

  # Quickstart: Chat with Azure OpenAI models using your own data

  - Article
  - 01/09/2025
  - 17 contributors

  Feedback

  Choose your preferred usage method

  PortalC#GoJavaScriptPythonRESTPowerShellSpringTypeScript

  In this article[Prerequisites](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#prerequisites-5)[Add your data using Azure AI Foundry portal](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#add-your-data-using-azure-ai-foundry-portal)[Retrieve resource information](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#retrieve-resource-information)[Create a Python environment](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#create-a-python-environment)Show 3 more

  In this quickstart, you can use your own data with Azure OpenAI models. Using Azure OpenAI's models on your data can provide you with a powerful conversational AI platform that enables faster and more accurate communication.

  

  ## Prerequisites

  The following resources:

  - [Azure OpenAI](https://portal.azure.com/#create/Microsoft.CognitiveServicesOpenAI)

  - [Azure Blob Storage](https://portal.azure.com/#create/Microsoft.StorageAccount-ARM)

  - [Azure AI Search](https://portal.azure.com/#create/Microsoft.Search)

  - An

     

    Azure OpenAI resource

     

    deployed in a

     

    supported region and with a supported model

    .

    - Be sure that you're assigned at least the [Cognitive Services Contributor](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/role-based-access-control#cognitive-services-contributor) role for the Azure OpenAI resource.

  - Download the example data from [GitHub](https://github.com/Azure-Samples/cognitive-services-sample-data-files/blob/master/openai/contoso_benefits_document_example.pdf) if you don't have your own data.

  [Reference](https://platform.openai.com/docs/api-reference?lang=python) | [Source code](https://github.com/openai/openai-python) | [Package (pypi)](https://pypi.org/project/openai/) | [Samples](https://github.com/openai/openai-cookbook/)

  These links reference the OpenAI API for Python. There's no Azure-specific OpenAI Python SDK. [Learn how to switch between the OpenAI services and Azure OpenAI services](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/switching-endpoints).

  

  ## Add your data using Azure AI Foundry portal

   Tip

  You can [use the Azure Developer CLI](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/azure-developer-cli) to programmatically create the resources needed for Azure OpenAI On Your Data

  Navigate to [Azure AI Foundry portal](https://ai.azure.com/) and sign-in with credentials that have access to your Azure OpenAI resource.

  1. You can either [create an Azure AI Foundry project](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/create-projects) by clicking **Create project**, or continue directly by clicking the button on the **Focused on Azure OpenAI Service** tile.

     [![A screenshot of the Azure AI Foundry portal landing page.](https://learn.microsoft.com/en-us/azure/ai-services/openai/media/use-your-data/ai-studio-homepage.png)](https://learn.microsoft.com/en-us/azure/ai-services/openai/media/use-your-data/ai-studio-homepage.png#lightbox)

  2. Select **Chat** under **Playgrounds** in the left navigation menu, and select your model deployment.

  3. In the **Chat playground**, Select **Add your data** and then **Add a data source**

     [![A screenshot of the chat playground in  Azure AI Foundry.](https://learn.microsoft.com/en-us/azure/ai-services/openai/media/use-your-data/chat-playground.png)](https://learn.microsoft.com/en-us/azure/ai-services/openai/media/use-your-data/chat-playground.png#lightbox)

  4. In the pane that appears, select **Upload files (preview)** under **Select data source**. Azure OpenAI needs both a storage resource and a search resource to access and index your data.

      Tip

     - See the following resource for more information:
       - [Data source options](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/use-your-data#supported-data-sources)
       - [supported file types and formats](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/use-your-data#data-formats-and-file-types)
     - For documents and datasets with long text, we recommend using the available [data preparation script](https://go.microsoft.com/fwlink/?linkid=2244395).

     1. For Azure OpenAI to access your storage account, you will need to turn on [Cross-origin resource sharing (CORS)](https://go.microsoft.com/fwlink/?linkid=2237228). If CORS isn't already turned on for the Azure Blob Storage resource, select **Turn on CORS**.
     2. Select your Azure AI Search resource, and select the acknowledgment that connecting it will incur usage on your account. Then select **Next**.

     [![A screenshot showing options for selecting a data source in Azure AI Foundry portal.](https://learn.microsoft.com/en-us/azure/ai-services/openai/media/quickstarts/add-your-data-source.png)](https://learn.microsoft.com/en-us/azure/ai-services/openai/media/quickstarts/add-your-data-source.png#lightbox)

  5. On the **Upload files** pane, select **Browse for a file** and select the files you downloaded from the [prerequisites](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#prerequisites) section, or your own data. Then select **Upload files**. Then select **Next**.

  6. On the **Data management** pane, you can choose whether to enable [semantic search or vector search](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/use-your-data#search-types) for your index.

      Important

     - [Semantic search](https://learn.microsoft.com/en-us/azure/search/semantic-search-overview#availability-and-pricing) and [vector search](https://azure.microsoft.com/pricing/details/cognitive-services/openai-service/) are subject to additional pricing. You need to choose **Basic or higher SKU** to enable semantic search or vector search. See [pricing tier difference](https://learn.microsoft.com/en-us/azure/search/search-sku-tier) and [service limits](https://learn.microsoft.com/en-us/azure/search/search-limits-quotas-capacity)
     - To help improve the quality of the information retrieval and model response, we recommend enabling [semantic search](https://learn.microsoft.com/en-us/azure/search/semantic-search-overview) for the following data source languages: English, French, Spanish, Portuguese, Italian, Germany, Chinese(Zh), Japanese, Korean, Russian, and Arabic.

  7. Review the details you entered, and select **Save and close**. You can now chat with the model and it will use information from your data to construct the response.

  

  ## Retrieve resource information

  You need to retrieve the following information to authenticate your application with your Azure OpenAI resource. This quickstart assumes you've uploaded your data to an Azure blob storage account and have an Azure AI Search index created. See [Add your data using Azure AI Foundry portal](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?pivots=programming-language-studio).

  - [Microsoft Entra ID](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_1_keyless)
  - [API key](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_1_api-key)

  Expand table

  | Variable name                | Value                                                        |
  | :--------------------------- | :----------------------------------------------------------- |
  | `AZURE_OPENAI_ENDPOINT`      | This value can be found in the **Keys & Endpoint** section when examining your Azure OpenAI resource from the Azure portal. An example endpoint is: `https://my-resoruce.openai.azure.com`. |
  | `AZURE_OPENAI_DEPLOYMENT_ID` | This value corresponds to the custom name you chose for your deployment when you deployed a model. This value can be found under **Resource Management** > **Deployments** in the Azure portal. |
  | `AZURE_AI_SEARCH_ENDPOINT`   | This value can be found in the **Overview** section when examining your Azure AI Search resource from the Azure portal. |
  | `AZURE_AI_SEARCH_INDEX`      | This value corresponds to the name of the index you created to store your data. You can find it in the **Overview** section when examining your Azure AI Search resource from the Azure portal. |

  Learn more about [keyless authentication](https://learn.microsoft.com/en-us/azure/ai-services/authentication) and [setting environment variables](https://learn.microsoft.com/en-us/azure/ai-services/cognitive-services-environment-variables).

  

  ## Create a Python environment

  1. Create a new folder named *openai-python* for your project and a new Python code file named *main.py*. Change into that directory:

  Windows Command Prompt

  ```cmd
  mkdir openai-python
  cd openai-python
  ```

  1. Install the following Python Libraries:

  - [OpenAI Python 1.x](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_1_python-new)
  - [OpenAI Python 0.28.1](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_1_python)

  Console

  ```console
  pip install openai
  pip install python-dotenv
  ```

  

  ## Create the Python app

  1. From the project directory, open the *main.py* file and add the following code:

  - [OpenAI Python 1.x](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_2_python-new)
  - [OpenAI Python 0.28.1](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python#tabpanel_2_python)

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

   Important

  For production, use a secure way of storing and accessing your credentials like [Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/general/overview). For more information about credential security, see the Azure AI services [security](https://learn.microsoft.com/en-us/azure/ai-services/security-features) article.

  1. Execute the following command:

  Windows Command Prompt

  ```cmd
  python main.py
  ```

  The application prints the response in a JSON format suitable for use in many scenarios. It includes both answers to your query and citations from your uploaded files.

  

  ## Clean up resources

  If you want to clean up and remove an Azure OpenAI or Azure AI Search resource, you can delete the resource or resource group. Deleting the resource group also deletes any other resources associated with it.

  - [Azure AI services resources](https://learn.microsoft.com/en-us/azure/ai-services/multi-service-resource?pivots=azportal#clean-up-resources)
  - [Azure AI Search resources](https://learn.microsoft.com/en-us/azure/search/search-get-started-portal#clean-up-resources)
  - [Azure app service resources](https://learn.microsoft.com/en-us/azure/app-service/quickstart-dotnetcore?pivots=development-environment-vs#clean-up-resources)

  

  ## Next steps

  - Learn more about [using your data in Azure OpenAI Service](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/use-your-data)
  - [Chat app sample code on GitHub](https://go.microsoft.com/fwlink/?linkid=2244395).

  ------

  ## Feedback

  Was this page helpful?

  YesNo

  [Provide product feedback ](https://feedback.azure.com/d365community/forum/79b1327d-d925-ec11-b6e6-000d3a4f06a4)|

  [Get help at Microsoft Q&A](https://learn.microsoft.com/answers/tags/387/azure-openai)

  ## Additional resources

  ------

  Training

  Module

  [Guided project: Build and Deploy your own AI Copilot - Training](https://learn.microsoft.com/en-us/training/modules/guided-project-build-deploy-your-own-ai-copilot/?source=recommendations)

  Build an AI copilot for Contoso Bike Shop. Integrate Azure OpenAI and Cosmos DB to enable advanced data searches, use GPT-3.5 for enhanced results, and deploy the solution on Azure Kubernetes Service.

  Certification

  [Microsoft Certified: Azure AI Engineer Associate - Certifications](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/?source=recommendations)

  Design and implement an Azure AI solution using Azure AI services, Azure AI Search, and Azure Open AI.

  ------

  Documentation

  - [Using your data with Azure OpenAI Service - Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/use-your-data?source=recommendations)

    Use this article to learn about using your data for better text generation in Azure OpenAI.

  - [Best practices for using Azure OpenAI On Your Data - Azure OpenAI Service](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/on-your-data-best-practices?source=recommendations)

    Learn about the best practices for using Azure OpenAI On Your Data, along with how to fix common problems.

  - [Use the Azure Developer CLI to deploy resources for Azure OpenAI On Your Data - Azure OpenAI Service](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/azure-developer-cli?source=recommendations)

    Use this article to learn how to automate resource deployment for Azure OpenAI On Your Data.

  Show 5 more

  

  [English (United States)](https://learn.microsoft.com/en-us/locale?target=https%3A%2F%2Flearn.microsoft.com%2Fen-us%2Fazure%2Fai-services%2Fopenai%2Fuse-your-data-quickstart%3Ftabs%3Dkeyless%2Ctypescript-keyless%2Cpython-new%26pivots%3Dai-foundry-portal)

  [Your Privacy Choices](https://aka.ms/yourcaliforniaprivacychoices)

  Theme

  - Manage cookies
  - [Previous Versions](https://learn.microsoft.com/en-us/previous-versions/)
  - [Blog](https://techcommunity.microsoft.com/t5/microsoft-learn-blog/bg-p/MicrosoftLearnBlog)
  - [Contribute](https://learn.microsoft.com/en-us/contribute/)
  - [Privacy](https://go.microsoft.com/fwlink/?LinkId=521839)
  - [Terms of Use](https://learn.microsoft.com/en-us/legal/termsofuse)
  - [Trademarks](https://www.microsoft.com/legal/intellectualproperty/Trademarks/)
  - © Microsoft 2025