Zero Knowledge Proof
This are steps to be followed while using Zokrates for zk-snark
# Install Zokrates using this command curl -LSfs get.zokrat.es | sh
## if you are using windows use wsl 

# Create a first.zok file where you write logic

# compile
zokrates compile -i first.zok

# perform the setup phase
zokrates setup

# execute the program
zokrates compute-witness -a 337 113569

# generate a proof of computation
zokrates generate-proof

# export a solidity verifier
zokrates export-verifier

# or verify natively
zokrates verify

![image](https://github.com/SuryaSan24x7/ZeroKnowlwdgeProof/assets/56404608/1b4c1599-1a9f-4b29-b6a6-c82e010d4ceb)
