# federated_learning
**Federated learning**: A deep learning technique to preserve user's data and also gets insights from that data without compromising the privacy of the user.</br>
**How it works?**</br>
The global model is sent to the client devices by the server, the client devices trains that model using their own local data and then share the learnt parameters
back with the server. Server then aggregates those parameters and updates the global model. Another round of federated training starts and client devices again trains
the global model with their local data, and the process continues for certain number of communication rounds.</br>
Dataset used: MNIST dataset.</br>
Client devices: 2 (virtual clients: jake and john)
