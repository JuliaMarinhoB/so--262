<img width="805" height="461" alt="1-Estado-Atual-Início" src="https://github.com/user-attachments/assets/6d3757c3-c119-4186-8a3a-3a66cabedb22" />

1-Estado Atual do Sistema, recursos totais 10 [R0], 5[R1] e 7[R2], recursos disponíveis 3[R0], 3[R1] e 2[R2]. Apresenta os processos P0,P1,P2,P3 e P4, o quanto já está alocado [C], em Máximo [Max] mostra o total necessário, em Necessidade [Need] mostra o quanto ainda precisa que o sistema forneça para concluir. 

<img width="708" height="762" alt="2-Estado-Seguro-Antes-Iniciar" src="https://github.com/user-attachments/assets/4f41929e-ef73-4761-af15-b06eb10fded4" />

2-Verificação do Estado Seguro, primeiro vê o Vetor Disponível então percorre a lista de processos, vê o primeiro que pode ser executado com o vetor que está disponível, executa o P e depois pega os todos os recursos disponíveis. Depois percorre novamente a lista para pegar o próximo que pode ser executado, segue essa linha até todos os processo serem atendidos e verificar o Estado Seguro e a Sequência Segura de Execução.  

<img width="787" height="865" alt="3-Tentativa-P1  1,0,2" src="https://github.com/user-attachments/assets/a151b689-02bf-4373-b096-8f2656ebc080" />

3-Solicitação de recursos pelo P1: [1,0,2], tentativa provisória. Sistema testa para ver se com essa solicitação inicial de P1 e com o restante dos recursos seria possível concluir todos os processo, faz essa verificação por meio da Verificação do Estado Seguro. Nesse caso é possível.

<img width="722" height="607" alt="4-Requisição-Atendida+P4-Bloqueado" src="https://github.com/user-attachments/assets/55a39490-ef93-401d-8cc6-0d4ad6cd28d3" />

4-Requisição foi concedida, logo atualiza-se o Estado Atual do Sistema, e faz-se uma solicitação de P4: [3,3,0], que foi recursada pois no Estado Atual do Sistema o recurso disponível é [2,3,0], portanto o processo foi bloqueado e P4 permanece na lista de espera.

<img width="708" height="392" alt="5-Estado-Atual-Final" src="https://github.com/user-attachments/assets/9a517b85-98c4-4de9-aa38-269809c4ad3a" />

5-Mostra o Estado Atual do Sistema final após a solicitação solicitada de P1 e a de P4 que foi bloqueada. 
