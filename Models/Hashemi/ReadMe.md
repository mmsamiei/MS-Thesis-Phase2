# Shahid Ali Hashemi Knowledge Selection Model

<p align="center">
<img src="https://newsmedia.tasnimnews.com/Tasnim/Uploaded/Image/1393/04/04/139304041648187843080544.jpg" align="center"
     alt="Shahid Ali Hashemi" width="360"/>
</p>

## Configuration

based on TinyBert which has 2 layer and 128 hidden dimension

Finetune only last layer of TinyBert

## Training Results

Best model i hashemi_52000steps with Error rate: 0.13823696991073608


## Recall Report For Hashemi56000

| Metric        | Test-Seen Dataset  | Test-Unseen Dataset  |
| ------------- |:-------------:| -----:|
| R@1           | 0.2290      | 0.1281 |
| R@2           | 0.3342      |   0.1885 |
| R@3           | 0.4090      |    0.2486 |
| R@4           | 0.4676      |    0.2999 |
| R@5           | 0.5261      |    0.3492 |
