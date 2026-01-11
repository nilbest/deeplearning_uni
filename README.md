For adding nbstripout to all .ipynb files for excluding all outputs repowide!
nbstripout --install --attributes .gitattributes
git add .gitattributes
git commit -m "Add nbstripout configuration"
git push


tensorflow braucht python 3.9-3.12
entweder über 

paru -S python310-bin

python3.10 -m venv .venv


sudo pacman -S pyenv
pyenv install 3.12




pyenv virtualenv 3.12 tfenv
pyenv activate tfenv


oder besser 
paru -S miniforge
echo "[ -f /opt/miniforge/etc/profile.d/conda.sh ] && source /opt/miniforge/etc/profile.d/conda.sh" >> ~/.zshrc
source ~/.zshrc
conda --version

conda create -n deeplearning-uni python=3.12
conda activate deeplearning-uni

conda install -r requirements.txt



https://developers.google.com/machine-learning/crash-course/prereqs-and-prework?hl=en
