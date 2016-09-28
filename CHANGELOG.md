# 0.8.0
* adds `Account.*JSON` functions

# 0.7.3
* adds `Chain.clone`

# 0.7.0
* updated peerDependency `bitcoinjs-lib` to `^2.0.0`

# 0.6.1
* adds `Chain.getChains`

# 0.6.0
* adds `Chain.getParent`, `new Chain(...).node` is now private
* changes `Chain` constructor to be lazy
* changes `Chain.indexOf` to `Chain.find`, returns undefined if not found

* adds `Account.getChain`
* removes `Account *(Internal|External)*` APIs, replaced with `*Chain*` API with chain index parameter
* changes `Account` constructor to only accept an array of `Chain`s

# 0.5.0
* removes `Account.getNode`
* changes `Account.getNodes` to `Account.getChildren`
* changes `AddressIterator` to `Chain`