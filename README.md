# EOS911

This is a Web app aimed at helping people retrieve their stolen EOS accounts.

There are 3 ways to use this:

- Using the EOS911 recovery website
- Proving ownership using a Hardware wallet
- Generating your keypairs offline

You can find out a more detailed run through @ https://blog.eos42.io/eos911-recovery-process/

## Dependencies

Just to be explicit on what we have used to build this tool, here is a list of all external code: 

- bootstrap: We arent css gurus, so bootstrap is pulled in from the web source
- web3.js: The ethereum js API
- eosjs-ecc: Official EOS js lib for elliptic curve cryptography functions
- jquery: Because we aren't hipster enough for the new stuff
- popper.js: Fancy tooltips
