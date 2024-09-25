mapping(address => uint) public balances;

function mint(address _to, uint _value) public {
    totalSupply += _value;
    balances[_to] += _value;
}

function burn(address _from, uint _value) public {
    require(balances[_from] >= _value, "Not enough balance");  // check if sender has enough balance to burn
    totalSupply -= _value;
    balances[_from] -= _value;
}
