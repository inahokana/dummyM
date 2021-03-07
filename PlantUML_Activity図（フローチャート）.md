```uml
@startuml
title （アクティビティ図）フローチャートの例

start

repeat
  :アクティビティA;
  note right
  アクティビティAは後判定繰り返し（repeat）
  end note
repeat while(i<10)

if( x>=0 ) then (true)
:アクティビティB
改行しました;
else (false)
endif

while(n<10)
:アクティビティC;
  note right
  アクティビティCは前判定繰り返し（while）
  end note
end while

stop
@enduml
```
