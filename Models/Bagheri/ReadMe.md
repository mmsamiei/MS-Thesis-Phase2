# Shahid Hasan Bagheri Knowledge Selection Model

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Hassan_Baqeri.jpg" align="center"
     alt="Shahid Ali Hashemi" width="360"/>
</p>

## Configuration

based on TinyBert which has 2 layer and 128 hidden dimension

Finetune both layers of TinyBert (Except embedding layer)

## Training Results

Best model is bagheri_30000steps with Error rate: 0.10485796456575414


## Recall Report For Bagheri30000

| Metric        | Test-Seen Dataset  | Test-Unseen Dataset  |
| ------------- |:-------------:| -----:|
| R@1           | 0.3105      | 0.2158 |
| R@2           | 0.4195      |   0.3118 |
| R@3           | 0.5094      |    0.3874 |
| R@4           | 0.5739      |    0.4478 |
| R@5           | 0.6273      |    0.5003 |

## Recall Report For Bagheri40000

| Metric        | Test-Seen Dataset  | Test-Unseen Dataset  |
| ------------- |:-------------:| -----:|
| R@1           | 0.3105      | 0.2170 |
| R@2           | 0.4195      |   0.3085 |
| R@3           | 0.5094      |    0.3851 |
| R@4           | 0.5739      |    0.4457 |
| R@5           | 0.6273      |    0.5011 |
