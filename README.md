# Extructure

1. Introduction                                (APROX. 1 PÁG.)
    Basic features on MOPs
MOEAs based on reference points for diversity assessment (MOEA/D, NSGA-III), in particular for Many-obj Optimization
    Basic features on static weight vector generation

2. Overview on weight vector design for reference-based MOEAs        (APROX. 2 PÁG.)
  * 2.1 Based on mixture designs
[Acá podrían venir los clásicos, Simplex Lattice y su transformación, Two Layers]
  * 2.2 Based on discrepancy functions
[Acá podrían venir UD Sobol, Hammerslay, etc.]

3. DU : problem statement                            (APROX. 2 PÁG.)
  * 3.1 Good lattice point
  * 3.2 Discrepancy functions
  * 3.3 Cd2 function and optimization problem for UD

4. Solution technique : parallel Tabu Search                    (APROX. 2 PÁG.)
  * 4.1 Decision variables and codification
  * 4.2 Neighborhood and Tabu list
  * 4.3 Specific features ( ? )
  * 4.4 Pruebas
  * 4.5 Nuevos Problemas Lap

5. Computational experiments and discussion                (APROX. 4 PÁG.)
    [Presentar el ajuste de parámetros de la búsqueda tabú]
    
  * 5.1 Uniform designs obtained
[Resultados obtenidos para 3, 5 y 8; comparación con otros resultados publicados; presentación de los diagramas de Coordenadas Paralelas y comparación con Simplex Lattice, por ej.]

   * 5.2 Testing on classical MO instances
[Aquí a discutir lo que se enseña. Propongo que mostremos resultados obtenidos:
     a. Con MOEA/D y con NSGA-III, para mostrar los beneficios del DU sin importar el algoritmo utilizado
     b. Sobre poquitas funciones: DTLZ2 y DTLZ7, el papalote y alguna invertida? Con las dimensiones 3, 5 y 8 de todas maneras.
     c. Comparando sólo con Simplex Lattice, y eventualmente con Two Layers ?
     d. Indicadores para comparar: HV, diversidad Delta? Agregamos la distancia de Haussdorf?]
 
6. Conclusions                                (APROX. 1 PÁG.)
References
