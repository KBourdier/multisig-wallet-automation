// SPDX-License-Identifier: GPL-3.0
pragma solidity 0.7.5;
contract Ownable{
    address internal owner;

    modifier onlyOwner {
        require(msg.sender == owner);
        _; //run the function
    }

    constructor(){
        owner = msg.sender;
    }
}
