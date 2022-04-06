# Knowledge-Augmented-Dialogue-Generation

## Overall Architecture
 <img src=https://user-images.githubusercontent.com/55969260/161927957-3f4192a3-ac0d-4df3-8517-2d45f15f5b13.png>

## Datasets
| Datasets                  | Business | Shopping | Food | Health |
|----------|:----:|:----:|:----:|:----:|
| Train | - | - | - | - |
| Valid | - | - | - | - |
| Test | - | - | - | - |

## Results
### Business
|Model|BLEU-1|BLEU-2|BLEU-3|BLEU-4|Dist-1|Dist-2|Entropy|
|:----------:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Base|27.68|11.67|6.37|3.96|35.14|74.22|10.24|
|QSim|28.09|12.22|6.65|4.11|38.39|78.83|10.35|
|RSim|-|-|-|-|-|-|-|
|QRSim<sup>†</sup>|-|-|-|-|-|-|-|

### Shopping
|Model|BLEU-1|BLEU-2|BLEU-3|BLEU-4|Dist-1|Dist-2|Entropy|
|:----------:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Base|-|-|-|-|-|-|-|
|QSim|-|-|-|-|-|-|-|
|RSim|-|-|-|-|-|-|-|
|QRSim<sup>†</sup>|-|-|-|-|-|-|-|

### Food
|Model|BLEU-1|BLEU-2|BLEU-3|BLEU-4|Dist-1|Dist-2|Entropy|
|:----------:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Base|-|-|-|-|-|-|-|
|QSim|-|-|-|-|-|-|-|
|RSim|-|-|-|-|-|-|-|
|QRSim<sup>†</sup>|-|-|-|-|-|-|-|

### Health
|Model|BLEU-1|BLEU-2|BLEU-3|BLEU-4|Dist-1|Dist-2|Entropy|
|:----------:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Base|-|-|-|-|-|-|-|
|QSim|-|-|-|-|-|-|-|
|RSim|-|-|-|-|-|-|-|
|QRSim<sup>†</sup>|-|-|-|-|-|-|-|

## ToDo
- [ ] Data-Preprocessing
- [X] Entropy
- [X] FiD
- [X] BART FiD
