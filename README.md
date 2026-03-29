# BlockInfo.sol
Contract deployed via Web3 BlockInfo.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BlockInfo {
    function getBlockNumber() public view returns (uint) {
        return block.number;
    }

    function getTimestamp() public view returns (uint) {
        return block.timestamp;
    }
}
