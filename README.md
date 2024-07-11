### Hi there 👋

```solidity
struct BlockchainArchitect {
    address identity;
    bytes32 title;
    bytes32 focus;
    uint256 experienceYears;
    bool openToCollaboration;
}

BlockchainArchitect public constant PROFILE = BlockchainArchitect({
    identity: 0xdenizumutdereli,
    title: bytes32("Senior Blockchain Architect"),
    focus: bytes32("DeFi protocols, DEX ecosystem"),
    experienceYears: 28,
    openToCollaboration: true
});
