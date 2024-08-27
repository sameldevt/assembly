compilar para objeto:

    nasm -f elf64 -o {nome_do_objeto}.o {nome_do_assembly}.asm

compilar para executavel:

    ld -m elf_x86_64 -s -o {nome_do_executavel} {nome_do_objeto}.o

como executar:

    ./{nome_do_executavel}