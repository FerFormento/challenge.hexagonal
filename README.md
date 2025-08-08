src/main/java/com/accenture/challenge/
 ├─ domain/
 │   ├─ model/         (PointVenta, CostEdge, Acreditacion)
 │   └─ service/       (interfaces de dominio)
 ├─ application/
 │   └─ usecase/       (implementaciones de casos de uso)
 ├─ ports/
 │   ├─ in/            (controllers DTOs)
 │   └─ out/           (repositorios, persistencia)
 ├─ infra/
 │   ├─ persistence/   (JPA repos)
 │   └─ cache/         (impl cache si se necesita)
 └─ web/
     └─ controller/    (rest controllers)
