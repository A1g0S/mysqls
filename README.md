# sqlmapls

<h4>A bash script to list sqlmap output</h4>
</br>
<h3>Usage:</h3>
sqlmapls example.com
cat $(sqlmapls example.com/dump/db_1/users.csv)
csv_reader --path $(sqlmapls example.com/dump/db_1/users.csv) -c user,password
