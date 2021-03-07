```uml
@startuml
title （アクティビティ図）フローチャートの例

start

:アクティビティA;
note right
アクティビティAのコメント
end note

if( x>=0 ) then (true)
:アクティビティB
改行しました;
else (false)
endif

repeat while(i<10)
:アクティビティC;
repeat

stop
@enduml
```
