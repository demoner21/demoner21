- 👋 Hi, I’m @demoner21
- 👀 I’m currently interested in learning Solidity && Javascript
- 📫 How to reach me +55 27 992 410 680 

//SPDX-License-Identifier: MIT

pragma solidity ^0.8.0;

contract hello {

    string public name = "Hello";

    function _updateName(string memory _newName) public {
        name = _newName;
    }

}
