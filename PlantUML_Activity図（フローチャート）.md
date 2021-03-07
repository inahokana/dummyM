```uml
@startuml
title （アクティビティ図）フローチャートの例

start

repeat
  :アクティビティA;
  note right
  アクティビティAのコメント
  end note
repeat while(i<10)

if( x>=0 ) then (true)
:アクティビティB
改行しました;
else (false)
endif

while(n<10)
:アクティビティC;
end while

stop
@enduml
```
