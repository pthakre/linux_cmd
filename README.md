# linux_cmd
helpful linux commands

> List all the files and folders from current directory and its subdirectory - ls -lRt 
> List all the files of folders which root name in that line - ls -lRt | grep "root"
> print all the files name which have root in the sentance while printing by ls -lRt --> ls -lRt | grep "root"|rev|cut -d' ' -f 1|rev
> sort in descending order -ls -lRt | grep "root"|rev|cut -d' ' -f 1|rev|sort | uniq
> Get all unques files name - > ls -lRt | grep "root"|rev|cut -d' ' -f 1|rev|sort | uniq|grep csv

root@ip-10-2-250-36:/home/bitnami/verticals/partners_files# ls -lRt | grep "root"|rev|cut -d' ' -f 1|rev|sort | uniq|grep csv
aliases.csv
answer_set.csv
assets.csv
collaterals.csv
current_incomes.csv
declaration_explanations.csv
dependents.csv
down_payments.csv
employers.csv
expenses.csv
housing_expenses.csv
liabilities.csv
relationships.csv
residences.csv
underwriting_verifications.csv
