# Candle
Simple PyTorch helpers. Example features:
* Simple modules like `Lambda`, `Flatten`, `View`, `Concat`, `Split`, `SkipConnection`.
* `NoInputSpec`, which wraps another module to dynamically figure out its input size the first time it's called.
* `CannedNet` and as an example generalisation `CannedResNet`, which provide a straightforward and extensible way to assemble sequential neural networks, but with some extra features, like not having to figure out input sizes, and easy specification of ResNet (or ResNet-in-ResNet etc.) style architectures.
* `create_supervised_trainer` for a simple trainer with all the boilerplate written for you. (Depends on the excellent `ignite` framework.)
* `Window` and `Recur` for a simple way to create complicated recurrent architectures.
* Utilities like `tensor_product` and `batch_flatten`.

Plus a few more things!
