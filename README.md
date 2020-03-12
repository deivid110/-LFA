# -LFApackage exercicio;

import javax.swing.JOptionPane;

public class coca {

public static void main(String[] args) {

JOptionPane.showMessageDialog(null, "Não devolvemos troco, insira o valor correto");

Integer[] value = { 10, 25 };

int valor = 0;

while (valor < 45) {
	
int moeda = JOptionPane.showOptionDialog(null, "apenas moedas de R$0,10 e R$0,25 ", "Moedas",

		JOptionPane.DEFAULT_OPTION, JOptionPane.DEFAULT_OPTION, null, value, value[0]);

if (moeda == 0) {
valor += 10;
} else if  (moeda == 1){
valor += 25;
}

}

JOptionPane.showMessageDialog(null, "aqui está sua coca");

}
} 
