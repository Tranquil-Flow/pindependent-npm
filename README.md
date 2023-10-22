Import into smart contract:

import "pindependence/PindependentGoerli.sol";

contract DeFiApp is Pindependent {
    constructor() {}
}

Replace import based on network your smart contract is on. Currently supports:

- PindependentGoerli
- PindependentPolygonZkEVMTestnet
- PindependentMantle
- PindependentScroll