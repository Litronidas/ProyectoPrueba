# ProyectoPrueba
 while (contadoAciertos < operacionesAcertar) {

            System.out.println("\nPROFESOR: ");

            oper1 = PedirDatosTeclado.pedirInt("\t\tIndique el primer operando: ");
            contadorNumeros++;
            
            operacion = PedirDatosTeclado.pedirChar("\t\tIndique la operacion matemática: ");

            while (operacion != '+' && operacion != '-' && operacion != '*' && operacion != '/') {
                System.out.println("\t\t\t\t" + Colores.RED + "Operación no permitida en el juego\n"
                        + "\t\t\t" + Colores.RED + "Recuerda que las operaciones permitidas son:\n"
                        + "\t\t\t\t" + Colores.RED + "* para multiplicar\n"
                        + "\t\t\t\t" + Colores.RED + "/ para dividir\n"
                        + "\t\t\t\t" + Colores.RED + "+ para sumar\n"
                        + "\t\t\t\t" + Colores.RED + "- para restar");
                operacion = PedirDatosTeclado.pedirChar("\t\tIndique la operacion matemática: ");
            }
