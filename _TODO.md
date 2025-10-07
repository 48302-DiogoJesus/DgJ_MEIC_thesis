- Update Optimization: assignment logic + other (preload, prewarm, taskdup)

- Add diagrams/images
    - Related Work
    - for serverless scheduling approaches
    - for WUKONG, to showcase choreographed scheduling

- Solution
    - need to mention that I use Redis 
    - metadata explain that the predictions calculate 
        for data transfer: speed rate
        for execution time: input_size ? recheck

    Client section:
    - executar planner
    - submeter o worklfow
    - esperar pela notificação que está completo + fazer download do resultado
    - gerar uma imagem do workflow sem o executar (semelhante ao Dask e WUKONG)
    - gerar uma imagem do plano também
    - um dashboard com uma visualização simples do DAG, onde dá para perceber a progressão do workflow

    - descrever mais os algoritmos, referindo simbolos
    - go deeper on each section of the architecture section
        - stopped at "Optimizations"