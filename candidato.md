# programacaoavancada
public class Candidato {
     private String nome;
    private int qtVoto;

     //construtor
    public Candidato(String nome) {
        qtVoto = 0;
        this.nome = nome;
    }
    
 //incremento
    public void incrementoVT(){
        qtVoto++;  
    }
    
    //metodos 
    public String getNome() {
        return nome;
    }

    public void setNome(String nome) {
        this.nome = nome;
    }

    public int getQtdVotos() {
        return qtVoto;
    }
}
