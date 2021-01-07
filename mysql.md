# MySQL
## SELECT Queries
| Command           | Output            |   
|---------------------------------------------------------|----------------------------------------------|   
| __SELECT__ * __FROM__ _`table1`_, _`table2`_,_..._ | select all colums from selected table(s)|   
|__SELECT__ _`field1`_, _`field2`_, _..._ __FROM__ _`table`_ | select specified columns from selected table | 
|__SELECT__ _fields_ __FROM__ _table_ __WHERE__ _conditions_ | select specified columns from selected table where specified conditions are met|
|__SELECT__ _fields_ __FROM__ _table_ __WHERE__ _conditions_ __ORDER BY__ field1, _field2_ | order output by specified field (default is ascending order)|
|__SELECT__ _fields_ __FROM__ _table_ __WHERE__ _conditions_ __ORDER BY__ _field1_, _field2_ __DESC__ | order output by specified fields in descending order|
|__SELECT__ _fields_ __FROM__ _table_ __WHERE__ _conditions_ __ORDER BY__ _field1_ __LIMIT__ _offset_, _count_ | Limit the output to __count__ entries, ommit __offset__ entries |
|__SELECT__ __COUNT__(_field_) __FROM__ _table_ __WHERE__ _conditions_ | return record count |


