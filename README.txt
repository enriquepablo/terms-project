Terms web
=========

Install
+++++++

pythonbrew use 3.3.0
git clone https://github.com/enriquepablo/terms-project.git
cd terms-project
pyvenv env
. env/bin/activate
python bootstrap.py -t
bin/buildout -N
serve -c /home/eperez/venvs/terms-project/etc/terms.cfg