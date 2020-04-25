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


| Metric        | Test-Seen Dataset  | Cool  |
| ------------- |:-------------:| -----:|
| R@1           | 0.2290 | $1600 |
| R@2           | 0.3342      |   $12 |
| R@3           | 0.4090      |    $1 |
| R@4           | 0.4676      |    $1 |
| R@5           | 0.5261      |    $1 |
