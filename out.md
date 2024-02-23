# Dúvidas sobre projetos Sui

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%290.png)

# Tese: Construa para além. Infraestrutura escalável, rápida, segura e acessível

# Disclaimer

As informações contidas neste documento não constituem, nem tampouco devem ser interpretadas como um conselho, recomendação, oferta e/ou solicitação para compra ou venda de criptoativos, ações, títulos, valores mobiliários e/ou de quaisquer outros instrumentos financeiros dentro de mercado de criptoativos.
Ao investidor, é recomendado formalmente a leitura cuidadosa do prospecto dos projetos,  _White Paper_, _Lite Paper_, Website do projeto e/ou outros documentos disponíveis sobre o ativo de modo a avaliar os riscos inerentes às transações e a determinar, de forma independente e por seu próprio julgamento e pesquisa realizada, sua capacidade de assumi-los.
As informações prestadas neste documento têm caráter meramente informativo, não constituindo oferta de venda e nem contemplando os termos jurídicos e comerciais pertinentes para serem consideradas como tal.
Ressaltamos ainda que o mercado de criptoativos é extremamente volátil e consequentemente de altíssimo risco. Faça sua própria pesquisa.


## 1) Consegue fazer um resumo da sui pra gente antes de seguirmos as perguntas?

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%291.png)

https://blockworks.co/news/four\-former\-facebook\-developers\-launch\-web3\-startup


* Proposta de valor:
  * Infraestrutura escalável, rápida, segura e acessível,  velocidade incomparável aliada a taxas baixas e previsíveis.
* Inovações:
  * Design centrado em objetos, Blocos de transações programáveis, Expressividade ilimitada, Garantia Atômica, Processamento de transações, Escalabilidade horizontal, Sui Move, Zero Provas de Conhecimento e zkLogin, Aluguel de estado \(Fundo\), etc.


## 2) Sui levantou mais de 300 milhões de VC. Qual sua opinião sobre isso? É bom para fomentar o ecossistema ou apenas um futuro dump dos VCs?

Discussão na live.

## 3) Se os caras falharam com a cripto do Facebook (Diem). Por que a cripto deles daria certo? Acabou o boicote? Compraram as pessoas certas?

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%292.png)


## 4) Uma das soluções da SUI é "os devs podem criar produtos inovadores com liquidez em um order book central nativo" Isso significa que não haverão DEX? Os swaps serão feitos nativamente na rede? Poderei ganhar renda passiva com isso?


## 5) Sempre q você menciona transações paralelas usa a palavra "algumas". Qual é a limitação desse paralelismo e como afeta a composabilidade da Sui?

* 1\) Transações paralelas
  * Transações que são independentes de qualquer outra ação, são consideradas transações simples e podem ser processadas _ sem passar por consenso_ .
    * Objetos próprios: Maioria dos ativos no Sui pertence a um único endereço.
  * Transações consideradas  _complexas e devem ser validadas por consenso_ .
    * Objetos compartilhados: têm propriedade compartilhada em várias contas.
* 2\) Composabilidade da Sui
  * Não afeta composabilidade na Sui.
  * Obs. 1: O paralelismo não está ligado direitamente a composabilidade.
    * Ex.: Eth é componível e não paralelizável, Sui é componível e paralelizável.
  * Obs. 2: A escalabilidade, em geral, é reduzida devido a composabilidade, pois são operações complexas.


## 6) Você já achou o Roadmap deles? Que pegadinha é essa de esconder Roadmap?

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%293.png)


---

https://forums.sui.io/t/sui-developer-roadmap-2024/45229

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%294.png)


---

https://forums.sui.io/t/sui-developer-roadmap-2024/45229

## 7) Ela usa ao mesmo tempo Blockchain e DAG para lidar com diferentes transações. Você acredita q isso pode ser um fator de vulnerabilidade/dificuldade de implementação/composabilidade? Qual a vantagem dessa divisão na estrutura de dados?

Ver, arquitetura do sistema. Próximo tela.


## Arquitetura do sistema

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%295.png)

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%296.png)

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%297.png)

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%298.png)


---

https://blog.sui.io/encode-club-sui-series-1/

* Sui utiliza um DAG na seu  _motor de _  _mempool_  _, _  _Narwhal_ .
  * É  _desacoplado de seu motor de consenso_ , Bullshark.
* Ao dissociar a  _disponibilidade de dados do consenso_ , o Sui é capaz de alcançar uma taxa de transferência muito maior ao custo de uma latência um pouco maior.


## 8) Você comentou que aparentemente não tinha como fazer MEV na rede. Ainda mantém essa opinião?



## Justiça nas transações MEV

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%299.png)

---

https://forums.sui.io/t/how-does-suis-mempool-differentiate-from-other-chains/45009/3

## Front-running

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%2910.png)

---

https://mirror.xyz/infinet.eth/nRtQjFs0fnJFEEFsuVoBzihE0uAU4loe-bKwgov_Z08

## 9) Vi que algumas coisas não precisam de consenso, como transações de alguns "objetos". Isso é uma gambiarra pra aumentar escalabilidade? Existem transações paralelas de fato na Sui?


## 10) Como de costume, compare a Sui com a Radix. Além do manifesto de transação, mais o que ela "copiou da Radix"?

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%2911.png)

![](assets%5C20240222-Live%20com%20GuiXRD%20%28Sui%2912.png)


