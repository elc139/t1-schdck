TOP500 & me: Comparativo de Arquiteturas Paralelas
--------------------------------------------------

Nome: Maurício Vielmo Schmaedeck

| Característica                                            | Computador no TOP500    | Meu computador            |
| --------------------------------------------------------- | ----------------------- | ------------------------- |
| Nome/Título                                               | OGBON                   | DESKTOP-U0KIF7Q           |
| Imagem (foto, diagrama, screenshot, etc.)                 | <img src="http://www.senaicimatec.com.br/wp-content/uploads/2019/11/1280862e-7f1f-4593-996b-79590a641ad3.jpg" height="96" /> | <img src="https://waz.vteximg.com.br/arquivos/ids/181944-1000-1000/96687-1-gabinete_nzxt_m59_classic_series_preto_m59_001bk_box-5.jpg?v=636529340851830000" width="96" />|
| Classificação de Flynn                                    | MIMD                    | MIMD                      |
| Memória: compartilhada, distribuída ou ambas?             | Ambas                   | Compartilhada             |
| Número total de núcleos de processamento                  | 27,768                  | 4                         |
| Fabricante e modelo do(s) processador(es)                 | Intel Xeon Gold 6240    | Intel® Core™ i5-4670      |
| Frequência do(s) processador(es)                          | 2.6 GHz                 | 3.40 GHz                  |
| Memória total                                             | 29,952 GB               | 16 GB                     |
| Tipo(s) de interconexão entre os núcleos/processadores    | UPI/Mellanox InfiniBand EDR | BGA-1364                  |
| Desempenho Linpack                                        | 1,605 TFlop/s           | 141,43 GFlop/s (best avg) |

### Linpack

O Linpack utilizado foi o `linpack_xeon64`, disponibilizado pela Intel no seu [site oficial](https://software.intel.com/en-us/articles/intel-mkl-benchmarks-suite).

O desempenho de 142,8083 GFlop/s foi a melhor média obtida nos 15 testes realizados pelo software. 

A melhor média foi obtida no teste com 5000 equações.

### Referências
- Top500. Ogbon Cimatec/Petrobras. [URL](https://top500.org/system/179703)
- Intel. Processador Intel® Core™ i5-4670. [URL](https://ark.intel.com/content/www/br/pt/ark/products/75047/intel-core-i5-4670-processor-6m-cache-up-to-3-80-ghz.html)
- WikiChip. Core i5-4670R - Intel. [URL](https://en.wikichip.org/wiki/intel/core_i5/i5-4670r)
- Renato Santino (OlharDigital). Conheça os 3 supercomputadores brasileiros entre os mais potentes do mundo. [URL](https://olhardigital.com.br/noticia/conheca-os-3-supercomputadores-brasileiros-entre-os-mais-potentes-do-mundo/96844).