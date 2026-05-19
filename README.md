public class Guitarra {

    // Atributos
    String marca;
    String modelo;
    int numeroCordas;

    // Construtor
    public Guitarra(String marca, String modelo, int numeroCordas) {
        this.marca = marca;
        this.modelo = modelo;
        this.numeroCordas = numeroCordas;
    }

    // Método para exibir informações
    public void exibirInformacoes() {
        System.out.println("Marca: " + marca);
        System.out.println("Modelo: " + modelo);
        System.out.println("Número de cordas: " + numeroCordas);
    }

    // Método principal (para testar)
    public static void main(String[] args) {
        Guitarra guitarra = new Guitarra("Fender", "Stratocaster", 6);
        guitarra.exibirInformacoes();
    }
}
