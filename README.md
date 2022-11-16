1. The contract simple storage, we save the person and add his fav number and
   retrieve them.
2. The contract storage factory is where we do the composability to call the simplestorage contract and deployed them and indexed them in a array, and retrieve the created contract address with the index val
3. The ExtraFactory SC we just inherited the fns from simple storage and overriden them to store fav num +5
