# linux_cmd
helpful linux commands

> List all the files and folders from current directory and its subdirectory - ls -lRt  <br>
> List all the files of folders which root name in that line - ls -lRt | grep "root"<br>
> print all the files name which have root in the sentance while printing by ls -lRt --> ls -lRt | grep "root"|rev|cut -d' ' -f 1|rev<br>
> sort in descending order -ls -lRt | grep "root"|rev|cut -d' ' -f 1|rev|sort | uniq<br>
> Get all unques files name - > ls -lRt | grep "root"|rev|cut -d' ' -f 1|rev|sort | uniq|grep csv<br>

root@ip-10-2-250-36:/home/bitnami/verticals/partners_files# ls -lRt | grep "root"|rev|cut -d' ' -f 1|rev|sort | uniq|grep csv<br>
aliases.csv<br>
answer_set.csv<br>
assets.csv<br>
collaterals.csv<br>
current_incomes.csv<br>
declaration_explanations.csv<br>
dependents.csv<br>
down_payments.csv<br>
