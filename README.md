# EC 518 Assignment 01

## How to run
1. I am using MultiClassNetwork for my best network
2. Load the MultiClassNetwork from network.py file
3. Load multi_net_best.t7 model
4. Run your own evealuation script or use the existing one

## Command to run scoring script
```
python main.py --mode score --arch multi_net
```

## Command to run evaluation script
```
python main.py --mode test --arch multi_net
```

## List of contributions
### Networks
1. ClassificationNetwork 
2. ClassificationSensorNetwork
3. MultiClassNetwork
4. RegressionNetwork

### Data augmentation
Follwoing are the methods implemented in imitations.py file
1. transform_data
2. horizontal_flip
3. remove_straight

### Dagger implementation

### Others
1. Modified record_imitations function to record observations and actions on demand
