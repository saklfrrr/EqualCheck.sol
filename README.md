# EqualCheck.sol
EqualCheck.sol
pragma solidity ^0.8.20;
contract EqualCheck {
    function isEqual(uint a, uint b) public pure returns(bool) {
        return a == b;
    }
}
