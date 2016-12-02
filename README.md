# blog-DeepLearning

1. How to install a virtualenv:

pip install virtualenv

construct a env: python /user/HS103/yx0001/.local/lib/python2.7/site-packages/virtualenv.py py_env_v3

openssl should be installed with python dir, not the virtualenv dir:
how to install openssl with python ?
/user/HS103/yx0001/.local/bin
./config --prefix=/user/HS103/yx0001/.local/bin
make all
make install
sth like : install ./doc/ssl/SSL_set_session.pod -> /user/HS103/yx0001/.local/bin/share/doc/openssl/html/man3/SSL_set_session.html

export PATH=/user/HS103/yx0001/.local/bin/:$PATH
export PYTHONPATH=/user/HS103/yx0001/.local/lib/python2.7/

virtualenv --python=/user/HS103/yx0001/.local/lib/python2.7/bin/python
