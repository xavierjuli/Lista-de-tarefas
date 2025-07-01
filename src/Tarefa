import java.time.LocalDateTime;

public class Tarefa {
    private int id;
    private String texto;
    private boolean concluida;
    private LocalDateTime dataalteracao;

    public Tarefa(int id, String texto, boolean concluida, LocalDateTime dataalteracao) {
        this.id = id;
        this.texto = texto;
        this.concluida = concluida;
        this.dataalteracao = dataalteracao;
    }

    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getTexto() {
        return texto;
    }

    public void setTexto(String texto) {
        this.texto = texto;
    }

    public boolean isConcluida() {
        return concluida;
    }

    public void setConcluida(boolean concluida) {
        this.concluida = concluida;
    }

    public LocalDateTime getDataalteracao() {
        return dataalteracao;
    }

    public void setDataalteracao(LocalDateTime dataalteracao) {
        this.dataalteracao = dataalteracao;
    }
    @Override
    public String toString() {
        return "[" + (concluida? "X": " ") +"]"+ texto+ "(Atualizado em: " + dataalteracao + ")";
    }

}
