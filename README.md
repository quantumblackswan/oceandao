## [OceanDAO Wiki](https://github.com/oceanprotocol/oceandao/wiki)
# 1. Clone your fork of OceanDAO repo
cd ~/Desktop
git clone https://github.com/quantumblackswan/oceandao.git
cd oceandao

# 2. Create the proposal file
mkdir -p round-XX/proposals
cd round-XX/proposals
nano qbond.md  # or use VSCode, Notepad++, etc.
# 3. Commit and push
cd ~/Desktop/oceandao

git add round-XX/proposals/qbond.md
git commit -m "Add Q-BOND Validator Memory Proposal — Round XX"
git push origin main
