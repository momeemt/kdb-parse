# kdb-parse
kdbのデータをjsonにする。科目番号、授業名、モジュール、時限、教室、備考がパースされる

## 注意
教室が不明の場合は、空白でパースされます。  
今年度開講されない科目はパースされません。  
レポジトリ内のCSVとJSONは、GitHub Actionsを使って、一週間おきに自動で更新されます。
