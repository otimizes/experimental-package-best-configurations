# experimental-package-best-configurations

https://figshare.com/s/783046b235074acba92b

Para replicar os experimentos, basta fazer o download da ferramenta [OPLA-Tool](https://github.com/otimizes/OPLA-Tool) e configurá-la utilizando as seguintes configurações:
| Descrição | População | Gerações | Aval. Aptidão | Operadores cruz. & mut. | Prob. Cruzamento | Prob. Mutação |
|---|---|---|---|---|---|---|
| Config1 | 100 | 300 | 30000 | FdC + CC & todos | 0.4 | 0.8 |
| Config2 | 100 | 300 | 30000 | FdC + MC & todos | 0.4 | 0.8 |
| Config3 | 200 | 15 | 3000 | FdC + CC & todos | 0.4 | 0.8 |
| Config4 | 200 | 15 | 3000 | FdC + MC & todos | 0.4 | 0.8 |
| Config5 | 200 | 15 | 3000 | FdC + CC & todos | 0.4 | 0.9 |
| Config6 | 200 | 15 | 3000 | FdC + MC & todos | 0.4 | 0.9 |

Após isto, devera seguir o tutorial disponível neste [link](https://drive.google.com/drive/folders/1OQUfpNfpu7i1fifDrg2NEeSAiFazc08j?usp=sharing) para coleta dos dados e experimentação. Após seguir todos os passos, você terá na planilha de normalização algumas medidas estatísticas relacionadas aos dados.

No mesmo link do tutorial, você também pode fazer o download do modelo de arquivo de script dos testes estatísticos utilizado neste trabalho. Basta baixar o arquivo, substituir os dados de exemplo pelos seus dados coletados (Hypervolume), e executar utilizando a ferramenta do R-Lang.

Em caso de dúvidos, envie-nos sugestões por meio de _issues_ e estaremos prontos para lhe responder.
