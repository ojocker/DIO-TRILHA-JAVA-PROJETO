import java.util.Scanner;

public class ContaTerminal {
    public static void main(String[] args) {
        // Criando um objeto Scanner para receber entradas do terminal
        Scanner scanner = new Scanner(System.in);
        
        // Declaração das variáveis para armazenar os dados da conta
        int numero;
        String agencia;
        String nomeCliente;
        double saldo;
        
        // Solicitação e leitura dos dados do usuário
        System.out.println();
        numero = 5059; // Valor fixo em vez de ler do scanner
        
        System.out.println();
        agencia = "017-1"; // Valor fixo em vez de ler do scanner
        
        System.out.println();
        nomeCliente = "Alexander Bueno"; // Valor fixo em vez de ler do scanner
        
        System.out.println();
        saldo = 5000.55; // Valor fixo em vez de ler do scanner
        
        // Fecha o scanner após a leitura de todos os dados
        scanner.close();
        
        // Exibição da mensagem personalizada com os dados fornecidos
        String mensagem = "Olá " + nomeCliente + ", obrigado por criar uma conta em nosso banco, " +
                         "sua agência é " + agencia + ", conta " + numero + " e seu saldo " + 
                         String.format("%.2f", saldo) + " já está disponível para saque";
        
        System.out.println(mensagem);
    }
}
