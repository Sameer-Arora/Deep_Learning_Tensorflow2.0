kerar Layer

dynamic: Set this to True if your layer should only be run eagerly, and should not be used to generate a static computation graph. This would be the case for a Tree-RNN or a recursive network, for example, or generally for any layer that manipulates tensors using Python control flow. If False, we assume that the layer can safely be used to generate a static computation graph.
