# postgres

In Ubuntu

cd `pg_config --sharedir`/tsearch_data

sudo cp unaccent.rules unaccent.rules.bk

sudo curl -O https://raw.githubusercontent.com/tuantrankim/postgres/master/contrib/unaccent/unaccent.rules

In pgadmin

CREATE  EXTENSION unaccent;

SELECT unaccent('phần mềm');