# AssertExample.sol
Remix - Deploy Contract On Base Network AssertExample.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AssertExample {
    uint public num = 10;

    function test() public view {
        assert(num == 10);
    }
}
