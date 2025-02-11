![DiffTrainer](https://github.com/agentasteriski/DiffTrainer/blob/main/assets/difftrainerlogo.png?raw=true)
# a CustomTkInter GUI for processing and training DiffSinger models
DiffTrainer brings together the most useful tools for DiffSinger in one easy, graphical package.
- [nnsvs-db-converter](https://github.com/UtaUtaUtau/nnsvs-db-converter) for converting wav+lab data to wav/ds+csv
- [DiffSinger](https://github.com/openvpi/DiffSinger)'s primary training
- OpenUtau export scripts
## setup options
### If you have never used Python:
- run python_installer.bat, go through the installer
- run setup.bat
- use run_gui.bat to launch after that

### If you have used Python:
- requires Python 3.10 specifically: [direct download for installer](https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe)
- if you would like a copy specifically installed in the DiffTrainer folder, you can use python_installer.bat instead
- once Python 3.10 is installed, setup.bat can be run to download the requirements, or do the usual `pip install -r requirements.txt`
- [Miniconda](https://docs.anaconda.com/free/miniconda/miniconda-other-installer-links/) is recommended for users of multiple Python versions.

## known bugs
- export ONNX fails if your checkpoint folder's name starts with t or n(yes really)

## language support
DiffTrainer uses [ez-localizr](https://github.com/spicytigermeat/ez-localizr/tree/main) to allow GUI language selection. All users are welcome to translate the text found in [en_US](/strings/en_US.yaml) to other languages and submit a pull request.

## to do
soon
- better readme
- use os.path.join instead of combining strings

eventually
- SOME for MIDI estimation
- fully support .ds training
- advanced export
- more translations
- an icon that isn't amogus
