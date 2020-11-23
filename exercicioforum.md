# forum
import  java.util.Scanner ;

public  class  App {
    
    public  static  boolean  ehBissexto ( int  ano ) {
        return ano %  400  ==  0  || (ano %  4  ==  0  && ano %  100  ! =  0 );
    }

    public  static  int  diasNoMes ( int  ano , int  mes ) {
        switch (mes) {
            caso  1 :
            caso  3 :
            caso  5 :
            caso  7 :
            caso  8 :
            caso  10 :
            caso  12 :
                return  31 ;
            
            caso  4 :
            caso  6 :
            caso  9 :
            caso  11 :
                return  30 ;
            
            caso  2 :
                if (ehBissexto (ano)) retornar  29 ;
                return  28 ;
            
            padrão :
                retorno  - 1 ;
        }
    }
    public  static  void  main ( String [] args ) {
        int ano, mes, dias;
        Entrada do scanner =  novo  scanner ( sistema . In);

        Sistema . para fora . println ( " Digite o ano " );
        ano = entrada . nextInt ();
        Sistema . para fora . println ( " Digite o mês " );
        mes = entrada . nextInt ();

        dias = diasNoMes (ano, mes);
        Sistema . para fora . printf ( " Dias no mês:% d \ n " , dias);
        entrada . fechar();

    }
}
