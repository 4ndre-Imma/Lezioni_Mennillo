    1  pwd
    2  cd ~
    3  mkdir lab_linux
    4  cd lab_linux/
    5  mkdir -p ./progetti/app_a ./progetti/app_p ./documenti ./backup
    6  touch ./progetti/app_a/main.py ./progetti/app_b/note.txt ./documenti/report.doc
    7  rm -r progetti/app_p
    8  mkdir progetti/app_b
    9  touch ./progetti/app_a/main.py ./progetti/app_b/note.txt ./documenti/report.doc
   10  cd progetti/app_a
   11  cd ../../
   12  cd documenti/../
   13  cd progetti/app_b
   14  cd ../../documenti/
   15  cd -
   16  cp ../app_a/main.py ../../backup/
   17  cp ../../documenti/report.doc ../../backup/report_backup.doc
   18  mv note.txt appunti.txt
   19  mv ../../documenti/report.doc ../../backup/
   20  cd ../../
   21  mv progetti/app_b/ progetti/app_beta
   22  echo <<parte 6 da finire>>
   23  history
