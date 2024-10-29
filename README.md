# Request-Prompt-Response-in-Same-Day-Delivery-Problem-with-Drone-Resupply
Contain the instance
Here are test samples in various environments provided in the paper; see the paper for detailed explanations of them.

You can load the samples as follows:
with open(train_file_path, 'rb') as f:
    train_set = pickle.load(f)
with open(test_file_path, 'rb') as f:
    test_set = pickle.load(f)

Each sample is a matrix with five rows:

The first row is the order ID,
The second row is the order generation time,
The third row is the latest delivery time,
The fourth row is the x-coordinate of the order,
The fifth row is the y-coordinate of the order.
The first column provides the depot's location information.
