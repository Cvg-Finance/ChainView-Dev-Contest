# LLAMAVIEW

## Utility

This ChainView script query a LLAMALEND market and return the current utilisation.

## Execute

install the relevant dependancy and ts-node then run:
1)

`npm install`

2) (optional) to (re) compile the chainview compatible smartcontract

`npx chainview compile`

3) To run the script, u can pass the address of a LLAMALEND market as parameter
(the address is optional, if not provided the default is to View CRV-long market)

`ts-node lend.ts 0xEdA215b7666936DEd834f76f3fBC6F323295110A`

## Resources 
https://github.com/Cvg-Finance/ChainView
