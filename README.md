# EOSIOAnalyzer

​	EOSIOAnalyzer is a static program analysis framework for EOSIO smart contract bytecode. It decompiles a Wasm bytecode program into an equivalent intermediate representation and constructs a corresponding CFG against it. This representation removes stack operations, thereby exposing dependencies between data due to stack properties. The resulting flow relationship between data is then fed into the Souffle analysis engine along with the Datalog specification written by the developer to extract program properties.

## Publications

- EOSIOAnalyzer: An Effective Static Analysis Vulnerability Detection Framework for EOSIO Smart Contracts

## Resources

- EOSIOAnalyzer 
- [Description](https://lwy0518.github.io/2021/12/13/EOSIOAnalyzer%E6%9E%B6%E6%9E%84/#more)
`password：Lwy`
- [Paper](https://github.com/lwy0518/final-paper/blob/master/EOSIOAnalyzer%EF%BC%9AAn%20Effective%20Static%20Analysis%20Vulnerability%20Detection%20Framework%20for%20EOSIO%20Smart%20Contracts.pdf)
- [Wasm instruction sets](http://www.dwenzhao.cn/profession/netbuild/webassemblyfunc.html#api8)