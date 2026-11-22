# CS-Group14


## 1. Code Structure


|-- server/ <br>
| |-- server.py # AsyncSSH transport + SFTP v3 loop (starter; harden it!) <br>
| |-- auth.py # password hashing/verification <br>
| |-- policy.py # DAC (*@$\wedge$@*) MAC (*@$\wedge$@*) RBAC gate + audit <br>
| '-- sftp_root/ # jail root (created at runtime; initially empty) <br>
|-- client/ <br>
| '-- client.py # SFTP client CLI (pwd/ls/mkdir/get/put/stat) <br>
|-- tests/ <br>
| '-- test_sftp.py # automated tests (optional but recommended) <br>
|-- CTF_writeup.pdf <br>
'-- README.md



## 2. Initial setup

### Install dependencies 

``` python3 -m venv .venv ```

On Mac/Linux: ``` source .venv/bin/activate ```

On Windows: ``` .venv\Scripts\activate ```


``` pip install requirements.txt ```








