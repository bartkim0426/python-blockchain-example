# Blockchain example by python

Make simple block and Blockchain by python. 


### Usage

Can make simple Blockchain.

```
from .blockchain import Blockchain

# make Blockchain
# automatically make genesis_block
new_blockchain = Blockchain()

# check block
new_blockchain.print_blocks()

# Add block by simple transactions

test_transactions = {
    'amount': 100,
    'sender': 'Kim',
    'receiver': 'Choi',
}
new_blockchain.add_block(test_transactions)
new_blockchain.print_blocks()
```


### Todo
[ ] Make to library
