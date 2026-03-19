# NotebookJupyter


GleysomAraujoDavid_rm56778_pbl_fase5.ipynb

Este repositório contem trabalho relacionado a FASE 5 do curdo de IA

https://www.youtube.com/watch?v=IhTsEQ1WG94  LINK DO VIDEO NO YOUTUBE.

Boa noite,

O sistema criado utilizou a cultura do feição como base para o desenvolvimento, realizando uma analise exploratorio nos dados fornecidos pela instituição, onde criamos um banco de dados que recebe valores enviados pelos sensores; esses dados são armazenados ms nuvem, onde podemos escalar a aplicação de acordo com o cresicmento so sietama, alimentado pelos dados; em seguida, utilizando algoritmos de aprendizado de maquina, para gerar um relatorio em cima dos dados apresentados, fornecendo informações vaçiosas para os gestores das fazendas.
De acordo com o que foi analizsado, o modelo RNA tem o melhor desempenho; p modelo RF tem o segundo melhor desempenho; o modelo SVW também apresentou um bom desempenho; o modelo RLM tem desempenho razoavel, e o pior desempenho foi o do modelo AD. Conclusão: o modelo RNA é o melhor para prever o rendimento de safra, seguindo de perto pelo modelo RF. Esses modelos podem ser usados para prever o rendimento de safra com base nas condições climáticas.

Para hospedar a máquina Linux na AWS, verificamos as opções mais baratas para as regiões de São Paulo e Virginia do Norte.
Considerando as configurações: 2 CPUs; 1GB de memória; até 5GB de rede;
50GB de armazenamento (HD), a instancia mais adequada pé a t3.micro, mas como vaos precisar de 2CPUs, considerei a t3.medium (2 vCPUs, 4 GB de RAM) para ter mais flexibilidade, mas o mais barato seria a t3.small.
Preços aproximados para instancias sob demanda (On Demand):
São Paulo (sa-eats-1): t3.medium $0,0832 por hora
Virginia do Norte (us-east-1): t3.medium $0,0416 por hora

Armazenamento EBS (50GB)
São Paulo: $0,10 por GB-mês ($5 por mês)
Virginia do Norte: $ 0,10 por GB-mês ($5 por mês)

Transferencia de dados: (até 5GB)
São Paulo: $0,14 por GB (para fora da região)
Virginia do Norte: $0,09 por GB (para fora da região.
Considerando tudo, a configuração mais barata seria na Virginia do Norte.

Tendo restrições legais para o armazenamento, no exterior, de dados coletados pelos sensores, optaria por armazenamento no Brasil, na região de Sâo Paulo, com instancias em localidades proximas, em outros datacenters, o que impede a latencia no momento em que eu precisar acessar os dados. 
