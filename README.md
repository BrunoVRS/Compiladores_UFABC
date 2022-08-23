# Compiladores_UFABC
Diretorio para materia da UFABC

Bruno Vieira Ramos Silva
11201811306

MAPEAMENTO FUNCIONALIDADES:

Checklist
1 Possui 2 tipos de variáveis -> LINHAS 131, 132 do IsiLang.g4

2 Possui a estrutura If.. else -> IsiLang.g4 LINHAS 216

3 1a Estrutura de Repetição -> IsiLang.g4 LINHAS 195

5 Possui operações de Entrada e Saída -> IsiLang.g4 LINHAS 149

6 Aceita números decimais -> IsiLang.g4 LINHAS 295

7 Verificar se variável foi declarada -> Linha 39 public void verificaID(String id) 

8 Verificar se variável declarada foi ou não usada -> public StringBuilder exibeVariaveisSemUsoWNG [isilang.g4] que através da program.getVarSemUso, sendo program uma instancia do IsiProgram.java [br.com.professorisidro.isilanguage.ast] que faz uso da variavel privada varSemAtrib [linha 24] da classe IsiProgram, que contém todas as variaveis sem atribuição. Essa marcação das variaveis sem atribuição é realizado na função generateTarget ainda no IsiProgram.Java que verifica quais ids (variaveis) fornecidas no codigo de input que tiveram um comando de atribuição associado [linha 29 do Isi program.java]. Aquelas que sequer tiveram uma atribuição, é porque não foram usadas e portanto, são mantidas na lista “varSemAtrib”.

9 Qual linguagem destino? (C/Java/Python) -> JAVA


https://youtu.be/CGmtz4oEYO4
