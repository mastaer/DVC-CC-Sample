## About DVC-CC
This branch was automated created with the tool DVC-CC. This tool connects DVC (https://dvc.org/) to CC (www.curious-containers.cc) to run your defined stages with DVC in a docker on your cloud system with CC. [More information about DVC-CC](https://github.com/deep-projects/dvc-cc)

## DVC-Status


<details><summary>Before Execution</summary>
<p>

```
Data and pipelines are up to date.

```

</p>
</details>




<details><summary>After Execution</summary>
<p>

```
	new:                draw_samples_output.ipynb
	new:                samples.npy

```

</p>
</details>



## How to rerun this experiment:
The following sections describe how you can rerun the dvc stages yourself.
### Pure command line (run the experiment local)
```
papermill draw_samples.ipynb draw_samples_output.ipynb --log-output -k python -p mean 10 -p std 3 -p num_of_samples 100 -p distribution normal

```
### Using DVC (run the experiment local)
```
dvc repro -P
```
### Using CC (run the experiment on a server)
```
faice exec cc_execution_file.red.yml
```
## Executed System
The scipt ran on the following system:


<details><summary>GPU(s)</summary>
<p>

```
                          name    memory.total [MiB]
====================================================
           GeForce GTX 1080 Ti             11175 MiB

```

</p>
</details>




<details><summary>Other Hardware</summary>
<p>

```
H/W path            Device  Class       Description
===================================================
/0/0                        memory      62GiB System memory
/0/1                        processor   AMD Ryzen 7 1800X Eight-Core Processor

```

</p>
</details>




<details><summary>Software</summary>
<p>

```
Package                Version        
---------------------- ---------------
absl-py                0.9.0          
ansiwrap               0.8.4          
appdirs                1.4.3          
asn1crypto             0.24.0         
astunparse             1.6.3          
async-generator        1.10           
atpublic               1.0            
attrs                  19.3.0         
backcall               0.1.0          
bcrypt                 3.1.7          
black                  19.10b0        
bleach                 3.1.4          
cachetools             4.0.0          
certifi                2019.11.28     
cffi                   1.14.0         
chardet                3.0.4          
click                  7.1.1          
cloudpickle            1.3.0          
colorama               0.4.3          
configobj              5.0.6          
cryptography           2.9            
cycler                 0.10.0         
decorator              4.4.2          
defusedxml             0.6.0          
distro                 1.5.0          
dpath                  2.0.1          
dvc                    0.93.0         
dvc-cc-agent           0.10.2         
dvc-cc-connector       0.8.1          
entrypoints            0.3            
flatten-json           0.1.7          
flufl.lock             3.2            
funcy                  1.14           
future                 0.18.2         
gast                   0.3.3          
gitdb                  4.0.4          
GitPython              3.1.1          
google-auth            1.12.0         
google-auth-oauthlib   0.4.1          
google-pasta           0.2.0          
grandalf               0.6            
grpcio                 1.27.2         
h5py                   2.10.0         
humanize               2.3.0          
idna                   2.6            
importlib-metadata     1.6.0          
inflect                3.0.2          
ipykernel              5.2.1          
ipython                7.13.0         
ipython-genutils       0.2.0          
ipywidgets             7.5.1          
jedi                   0.17.0         
Jinja2                 2.11.2         
joblib                 0.14.1         
jsonpath-ng            1.5.1          
jsonschema             3.2.0          
jupyter                1.0.0          
jupyter-client         6.1.3          
jupyter-console        6.1.0          
jupyter-core           4.6.3          
Keras-Preprocessing    1.1.0          
keyring                10.6.0         
keyrings.alt           3.0            
kiwisolver             1.2.0          
Markdown               3.2.1          
MarkupSafe             1.1.1          
matplotlib             3.2.1          
mistune                0.8.4          
nanotime               0.5.2          
nbclient               0.2.0          
nbconvert              5.6.1          
nbformat               5.0.6          
nest-asyncio           1.3.2          
networkx               2.3            
notebook               6.0.3          
numpy                  1.18.2         
oauthlib               3.1.0          
opt-einsum             3.2.0          
packaging              20.3           
pandas                 1.0.3          
pandocfilters          1.4.2          
papermill              2.1.0          
paramiko               2.7.1          
parso                  0.7.0          
pathspec               0.8.0          
pexpect                4.8.0          
pickleshare            0.7.5          
Pillow                 7.1.1          
pip                    20.0.2         
ply                    3.11           
prometheus-client      0.7.1          
prompt-toolkit         3.0.5          
protobuf               3.11.3         
ptyprocess             0.6.0          
pyasn1                 0.4.8          
pyasn1-modules         0.2.8          
pycparser              2.20           
pycrypto               2.6.1          
pydot                  1.4.1          
Pygments               2.6.1          
pygobject              3.26.1         
pygtrie                2.3.2          
pyjson                 1.3.0          
PyNaCl                 1.3.0          
pyparsing              2.4.7          
pyrsistent             0.16.0         
python-apt             1.6.5+ubuntu0.2
python-dateutil        2.8.0          
pytz                   2019.3         
pyxdg                  0.25           
PyYAML                 5.3.1          
pyzmq                  19.0.0         
qtconsole              4.7.3          
QtPy                   1.9.0          
red-connector-ssh      1.2            
regex                  2020.4.4       
requests               2.23.0         
requests-oauthlib      1.3.0          
rsa                    4.0            
ruamel.yaml            0.16.10        
ruamel.yaml.clib       0.2.0          
scikit-learn           0.22.2.post1   
scipy                  1.4.1          
scp                    0.13.2         
seaborn                0.10.0         
SecretStorage          2.3.1          
Send2Trash             1.5.0          
setuptools             46.1.3         
shortuuid              1.0.1          
six                    1.14.0         
sklearn                0.0            
smmap                  3.0.2          
tenacity               6.1.0          
tensorboard            2.2.0          
tensorboard-plugin-wit 1.6.0.post2    
tensorflow-estimator   2.2.0rc0       
tensorflow-gpu         2.2.0rc2       
tensorflow-probability 0.9.0          
termcolor              1.1.0          
terminado              0.8.3          
testpath               0.4.4          
texttable              1.6.2          
textwrap3              0.9.2          
toml                   0.10.0         
torch                  1.4.0          
torchvision            0.5.0          
tornado                6.0.4          
tqdm                   4.45.0         
traitlets              4.3.3          
treelib                1.6.1          
typed-ast              1.4.1          
urllib3                1.25.8         
voluptuous             0.11.7         
wcwidth                0.1.9          
webencodings           0.5.1          
Werkzeug               1.0.0          
wheel                  0.30.0         
widgetsnbextension     3.5.1          
wrapt                  1.12.1         
zc.lockfile            2.0            
zipp                   3.1.0          

```

</p>
</details>


