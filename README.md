// SPDX-License-Identifier: MIT
pragma solidity >=0.8.9;

contract MyContract {
    uint public myNumber;
    string public myString;
    bool public myBool;
    address public myAddress;

    function setMyNumber(uint _number) public returns (uint) {
        myNumber = _number;
        return myNumber;
    }

    function getMyNumber() public view returns (uint) {
        return myNumber;
    }

    function setMyString(string memory _string) public returns (string memory) {
        myString = _string;
        return myString;
    }

    function getMyString() public view returns (string memory) {
        return myString;
    }

    function setMyBool(bool _bool) public returns (bool) {
        myBool = _bool;
        return myBool;
    }

    function getMyBool() public view returns (bool) {
        return myBool;
    }

    function setMyAddress(address _address) public returns (address) {
        myAddress = _address;
        return myAddress;
    }

    function getMyAddress() public view returns (address) {
        return myAddress;
    }
}
