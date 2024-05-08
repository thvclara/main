class Animal {
    private String nome;
    private int idade;

    public Animal(String nome, int idade) {
        this.nome = nome;
        this.idade = idade;
    }

    public String getNome() {
        return nome;
    }

    public void setNome(String nome) {
        this.nome = nome;
    }

    public int getIdade() {
        return idade;
    }

    public void setIdade(int idade) {
        this.idade = idade;
    }
}

class Mamifero extends Animal {
    private String tipoAlimento;
    private double valorAlimentacao;

    public Mamifero(String nome, int idade, String tipoAlimento, double valorAlimentacao) {
        super(nome, idade);
        this.tipoAlimento = tipoAlimento;
        this.valorAlimentacao = valorAlimentacao;
    }

    public String getTipoAlimento() {
        return tipoAlimento;
    }

    public void setTipoAlimento(String tipoAlimento) {
        this.tipoAlimento = tipoAlimento;
    }

    public double getValorAlimentacao() {
        return valorAlimentacao;
    }

    public void setValorAlimentacao(double valorAlimentacao) {
        this.valorAlimentacao = valorAlimentacao;
    }
}

public class Main {
    public static void main(String[] args) {
        Mamifero mamifero = new Mamifero("Cachorro", 3, "Ração", 100.0);

        System.out.println("Nome do mamífero: " + mamifero.getNome());
        System.out.println("Idade do mamífero: " + mamifero.getIdade());
        System.out.println("Tipo de alimento do mamífero: " + mamifero.getTipoAlimento());
        System.out.println("Valor da alimentação do mamífero: " + mamifero.getValorAlimentacao());
    }
}
