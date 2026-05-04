# VotingSimple.sol
VotingSimple.sol
pragma solidity ^0.8.20;
contract VotingSimple {
    uint public yes;
    uint public no;

    function vote(bool choice) public {
        if(choice) yes++;
        else no++;
    }
}
