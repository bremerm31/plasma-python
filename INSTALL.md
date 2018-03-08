# Installation instructions

## Maverick

Log onto Maverick using your TACC accound
```bash
ssh <username>@maverick.tacc.utexas.edu
```
Before building the library, run
```bash
module load gcc/4.9.1 cuda/8.0 cudnn/5.1 python3/3.5.2 tensorflow-gpu/1.0.0
```
and clone the `plasma-python`. From the root directory of the reposity, run
```bash
python3 setup.py install --user
```
to build the repository.