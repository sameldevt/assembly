compilar para objeto:

    nasm -felf64 {nome_do_asm}.asm -o {nome_do_objeto}.o

compilar para executavel:

    ld -o {nome_do_executavel} {nome_do_objeto}.o

como executar:

    ./{nome_do_executavel}