## POO
package poo_ejercicio_propuesto12;

public class POO_Ejercicio_Propuesto12 {
    
    public static void main(String[] args) {
        double horas_trabajadas, valor_hora, retencion, salario_bruto, salario_neto;
        
        valor_hora = 5000;
        horas_trabajadas = 48;
        salario_bruto = valor_hora * horas_trabajadas;
        retencion = salario_bruto * (12.5/100);
        salario_neto = salario_bruto - retencion;
        
        System.out.println("Las horas trabajadas son "+ horas_trabajadas + " horas" );
        System.out.println("EL valor de la hora es "+ valor_hora + " Pesos" );
        System.out.println("El salario bruto es "+ salario_bruto + " Pesos" );
        System.out.println("La retencion en la fuente es "+ retencion + " Pesos" );
        System.out.println("El salario neto del trabajador es "+ salario_neto + " Pesos" );      
    }
    
}
