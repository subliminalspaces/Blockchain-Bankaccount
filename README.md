# Blockchain-Bankaccount-
Creates a smart contract on the tron blockchain that can store funds, and user can withdraw with password.

Included is the original smart contract deployment address.  
If you want to to deploy the smart contract on the blockchain.  I suggest tronbox.  
You can pick a password by swapping it out for the provided one in the contract.
You can deposit funds by sending to the generated contract address.

npm install to install the dependencies.  

Configure the tronWeb object with a valid tron wallet.

Then swap out the provided contract address for the one generated by your contract migration. Put your password in the withdraw function, and specify
how much you want to withdraw in units of Suns with 1,000,000 Suns being 1 tron.

You should then be good to go.  Fee limit and Call value you should adjust if you get OUT OF ENERGY errors.  shouldPollResponse
will make the console wait for a response.  I prefer to have it set to true.
