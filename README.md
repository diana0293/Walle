Proyecto Walle

 Funciones a Realizar:
Inicio (padre: ninguno, hijo: encenderRobot)
└── encenderRobot(estado) (padre: Inicio, hijo: encenderLamparas)
  └── encenderLamparas(ojos) (padre: encenderRobot, hijo: mantenerFuncionamiento)
    └── mantenerFuncionamiento(reloj) (padre: encenderLamparas, hijo: verificarEnergia)
      └── verificarEnergia(pila) (padre: mantenerFuncionamiento, hijos: apagarLamparas [si SÍ], mantenerFuncionamiento [si NO])
        ├── mantenerFuncionamiento(reloj) (bucle si NO hay energía)
        └── apagarLamparas(ojos) (padre: verificarEnergia, hijo: apagarRobot)
          └── apagarRobot(estado) (padre: apagarLamparas, hijo: Fin)
            └── Fin (padre: apagarRobot, hijo: ninguno)







González Cruz Diana
