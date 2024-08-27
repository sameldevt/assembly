Registradores:
| Nome        | Alias  | Descrição                                                             |
|-------------|--------|-----------------------------------------------------------------------|
| r0          | rax    | Uma espécie de "acumulador," usado em instruções aritméticas. Por exemplo, uma instrução `div rcx`, um número grande de 128 bits, gera restos em dois registradores: `rdx` e `rax`. Dividido por `rcx`, o resto é armazenado novamente em `rax`.                              |
| r1          | rcx    | Usado para ciclos (por exemplo, em loop).                             |        
| r2          | rdx    | Armazena dados durante operações de entrada/saída                     |          
| r3          | rbx    | Registrador base. Era usado para endereçamento de base nos primeiros  |
|             |        | modelos do processador.                                               |
| r4          | rsp    | Armazena o endereço do elemento do topo da pulha de hardware.         |        
| r5          | rbp    | Base do stack frame.                                                  | 
| r6          | rsi    | Índice de origem em comandos de manipulação de strings (como mvsd)    |
| r7          | rdi    | Índice de origem em comandos de manipulação de strings (como mvsd)    |
| r8          |        |                                                                       |
| r9 - r15    | não há |                                                                       |