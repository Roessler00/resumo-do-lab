# ☁️ Tipos de Serviço em Nuvem + Modelo de Responsabilidade Compartilhada

Fala, dev! 👋  
Se você tá mergulhando no mundo da computação em nuvem (cloud computing), cola aqui que esse guia vai te dar aquela visão geral afiada ⚡. Vamos falar sobre os tipos de serviços na nuvem (IaaS, PaaS e SaaS) e entender como funciona o **modelo de responsabilidade compartilhada** 🔐.

---

## 🧩 1. Tipos de Serviços de Nuvem

A computação em nuvem oferece três principais modelos de serviço. Cada um entrega diferentes níveis de controle, flexibilidade e gerenciamento.

| Modelo      | Significado                   | O que o cliente gerencia?                      | Exemplos                                        |
| ----------- | ----------------------------- | ---------------------------------------------- | ----------------------------------------------- |
| 🏗️ **IaaS** | _Infrastructure as a Service_ | Sistemas operacionais, apps, dados, middleware | Microsoft Azure, AWS EC2, Google Compute Engine |
| 🛠️ **PaaS** | _Platform as a Service_       | Aplicações e dados                             | Azure App Service, Google App Engine, Heroku    |
| 💻 **SaaS** | _Software as a Service_       | Apenas usa o software                          | Microsoft 365, Gmail, Salesforce, Dropbox       |

> 💡 **Resumo Rápido**:
>
> - IaaS = Você monta tudo.
> - PaaS = Você só desenvolve.
> - SaaS = Você só usa.

---

## 🤝 2. Modelo de Responsabilidade Compartilhada

Com a nuvem, a segurança e a gestão são divididas entre você (cliente) e o provedor de nuvem. Mas **quem cuida do quê**? 👀

Vamos ver isso de forma visual com uma tabela:

| Componente                  | On-Premise 🏢 | IaaS 🏗️     | PaaS 🛠️     | SaaS 💻     |
| --------------------------- | ------------- | ----------- | ----------- | ----------- |
| Aplicações                  | ✅ Cliente    | ✅ Cliente  | ✅ Cliente  | ❌ Provedor |
| Dados                       | ✅ Cliente    | ✅ Cliente  | ✅ Cliente  | ✅ Cliente  |
| Tempo de Execução (Runtime) | ✅ Cliente    | ✅ Cliente  | ❌ Provedor | ❌ Provedor |
| Middleware                  | ✅ Cliente    | ✅ Cliente  | ❌ Provedor | ❌ Provedor |
| Sistema Operacional         | ✅ Cliente    | ✅ Cliente  | ❌ Provedor | ❌ Provedor |
| Virtualização               | ✅ Cliente    | ❌ Provedor | ❌ Provedor | ❌ Provedor |
| Servidores                  | ✅ Cliente    | ❌ Provedor | ❌ Provedor | ❌ Provedor |
| Armazenamento               | ✅ Cliente    | ❌ Provedor | ❌ Provedor | ❌ Provedor |
| Rede                        | ✅ Cliente    | ❌ Provedor | ❌ Provedor | ❌ Provedor |
| Data Center Físico          | ✅ Cliente    | ❌ Provedor | ❌ Provedor | ❌ Provedor |

> 🎯 **Resumo esperto**: Quanto mais você sobe na escada (IaaS → PaaS → SaaS), **menos responsabilidade técnica** você tem. Mas, atenção: os **dados** ainda são sua responsabilidade!

---

## 📌 Conclusão

Saber diferenciar os modelos de serviço e como funciona o modelo de responsabilidade é essencial pra mandar bem na cloud e até gabaritar certificações como a **AZ-900** ou a **AI-900** 🧠🚀

Se liga:

- IaaS te dá mais controle, mas também mais responsabilidade 🛠️
- PaaS é o meio termo pra quem só quer codar sem se preocupar com o resto 💻
- SaaS é plug-and-play: só usar e ser feliz 😄

---

## 🚀 Dica de Estudo

Tá se preparando pra certificação? Confere essas formações gratuitas na DIO:

- [Formação Fundamentos em Cloud AWS](https://web.dio.me/track/cloud-computing) ☁️
- [Formação Microsoft Azure Fundamentals](https://web.dio.me/track/formacao-azure-fundamentals) 🔐
- [Curso de Fundamentos em IA com Azure](https://web.dio.me/track/formacao-inteligencia-artificial-fundamentals) 🤖

---

## 🧠 Bora continuar?

Salva esse repositório ⭐  
Compartilha com a galera que tá estudando cloud 🔄  
E não esquece de me seguir pra mais conteúdos como esse 👊

---

Feito com 💙 por **João Roessler**
