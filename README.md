# detectron2


### Environment setup
1. create a new environment using below command.

```
conda create -n env_name python=3.8
```
2. install pytorch using below command.
```
pip install torch==1.12.1+cu102 torchvision==0.13.1+cu102 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu102
```
3. now clone this current repo using below example.
```
git clone "repo_dir"
```
4. go to the clone directory.
```
cd detectron2
```
5. now install the detectron2 using local repository.
```
python -m pip install -e .
```

6. or use the install below command to install detectron2 using git+ command.
```
python -m pip install 'git+https://github.com/Frinks-ai/detectron2'
```