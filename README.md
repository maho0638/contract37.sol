# contract37.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Solidity mapping for Web3 apps
contract Contract37 {
    mapping(address => uint) public balances;

    function setBalance(uint amount) public {
        balances[msg.sender] = amount;
    }
}
