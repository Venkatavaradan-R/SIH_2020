#  SIH_2020
hi. we are blessed by lord srujan.

This repo contains a proof of concept for the problem statememt chosen.

PS: Software for computerization of farmer, land details along with beneficiary schemes details

PS no : DS157

Organization : Dr. B R Ambedkar Institute of Technology


Built a blockchain solution for this, using etherium (free open source blockchain network), metamask (payment gateway), ganache (Local blockchain for testing and development), truffle (the compiler).

instructions to run:

1. clone the repo.
2. open ganache and run a blockchain test env.
  ganche gui can be downloaded from https://www.trufflesuite.com/ganache
  create a workspace
  open metamask extenion in firefox (or whatever) and make sure both are synced to same workspace.
3. run npm install in the cloned repo
4. truffle migrate --reset (remove --reset if you dont want to delete all the info on your blockchain that you create before)
5. npm run dev


EXTRA NOTES & DEBUGGING: For some reason truffle config and app.js file names vary depending on what os youre using. 
  For linux, make sure that its app.js and truffle.js
  For windows, make sure its App.js and truffle-config.js


Project Timeline details:
  Start date: 5th Feb 2020
  End date : 8th Feb 2020
  Time spent(approx.) : 32hrs
