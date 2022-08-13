        // SPDX-License-Identifier: MIT

pragma solidity 0.8.7;

    contract Coin {
        
        uint256 public TSupply;
        uint256 public Tax;



        Holders[] public holder;
        struct Holders  {
            string name;
            uint256 balance;
        }
        

        function SetTax () public returns (uint256){
            Tax = TSupply * 2/100;
            return Tax;
        }

        function SetTSupply (uint256 _NewSupply) public{
            TSupply = _NewSupply;
        }
        
        function AddTax () public returns (uint256){
            TSupply = TSupply + Tax; 
            return TSupply;
        }

        function SubstractTax() public returns (uint256){
            TSupply = TSupply - Tax;
            return TSupply;
        }

        
        function addHolder (string memory _name  ,uint256 _balance)public{ 
            holder.push(Holders(_name,_balance));    
        
      

}
    }
