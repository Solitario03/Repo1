# Repo1
- archivo de prueba
- es para editar
- solo insanidad
  

@startuml
class EstadisticaBase {
    +metodoBase()
}

class EstadisticaCualitativa {
    +metodoCualitativa()
}

class EstadisticaCuantitativa {
    +metodoCuantitativa()
}

class Main {
    +metodoMain()
}

EstadisticaBase <|-- EstadisticaCualitativa
EstadisticaBase <|-- EstadisticaCuantitativa
EstadisticaCualitativa <|-- Main
EstadisticaCuantitativa <|-- Main

@enduml


