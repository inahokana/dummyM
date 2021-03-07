```uml
@startuml
title （アクティビティ図）フローチャートの例

start

:iに0を代入;

repeat
  :アクティビティA;
  note right
  アクティビティAは後判定繰り返し
  end note
repeat while (i<10)

if( x>=0 ) then (true)
:アクティビティB
改行しました;
else (false)
endif

:nに0を代入;

while(n<10)
:アクティビティC;
  note right
  アクティビティCは前判定繰り返し
  end note
end while

stop
@enduml
```
