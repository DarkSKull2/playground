

find ./ -name '*.java' | xargs javac -d mods/org.rsantos.typeeditor



 
java --module-path mods -m org.rsantos.typeeditor/org.rsantos.typeeditor.FXMLTableView
 
 
